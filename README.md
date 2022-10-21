# Ideas

Some overdone, some smart ideas for anyone to build on top of.

If any of the following ideas already exist OR if you (decide to) build one, let me know: [arnav@arnavgosain.com](mailto:arnav@arnavgosain.com)

# Database Agnostic Event Ingestion Service

Amplitude, Segment and the like can be obscenely expensive if you run a large consumer app that sends 10s of millions of events a month.

I'd like a subset of Amplitude that is as an opensource ingestion service that can connect to my db of choice (Snowflake, BigQuery, Redshift, etc) and just stores events after enrichment.

I can then use a project like [Atlas](https://github.com/mjirv/atlas) to analyse this data.

Keywords: Data warehouse, Data ownership, Analytics




