# Ideas

Some good, some bad ideas for anyone to build.

If any of the following ideas already exist OR if you (decide to) build one, let me know: [arnav@arnavgosain.com](mailto:arnav@arnavgosain.com)

# Database Agnostic Event Ingestion Service

Amplitude, Segment and the like can be obscenely expensive if you run a large consumer app that sends 10s of millions of events a month.

I'd like a subset of Amplitude that is as an opensource ingestion service that can connect to my db of choice (Snowflake, BigQuery, Redshift, etc) and just stores events after enrichment.

I can then use a project like [Atlas](https://github.com/mjirv/atlas) to analyse this data.

Keywords: Data warehouse, Data ownership, Analytics


# Firebase for Data Engineering

Firebase empowered frontend engineers to build full-stack apps. With one SDK, you can start with Authentication/Authorization and a NoSQL databases, theng progressively use analytics, hosting, serverless functions, and more as and when needed.

I've not found anything so far that does the same for common data engineering requirements. Can we empower web developers to work on data problems, without the overhead of having to learn data engineering from scratch?

I imagine it to be something like Firebase, where you can start with say, ELT & warehousing, and then grow into transformation, governance, reverse ETL, et cetera.
