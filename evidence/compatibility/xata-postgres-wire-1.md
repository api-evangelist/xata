<!-- fetched 2026-10-13 from https://xata.io/ by sweep-shape-compat.py; text extracted from the provider's own page -->

Xata – the branch native Postgres platform 
 Product 
 Solutions 
 Blog 
 Docs 
 Pricing 
 12.2k 
 12.2k Log in Sign up 
 Xata is open source ⭐ Star the repository
 Xata is open source ⭐
 Branch your production Postgres
for every coding agent
 Start fresh or branch an existing Postgres in seconds. Scale to zero when idle.
One database per agent task, pull request, preview, or CI run.
 Get started Watch a demo 
 14 days free. No credit card required.
 A production Postgres database branches into two active isolated environments while capacity lanes represent hundreds more production-like branches.
 PR #846
 Cart totals
 Cursor task
 Add index
 Preview
 search-v2
 CI
 migration-228
 PR #847
 Invoice export
 Claude task
 Backfill data
 Preview
 dashboard-v3
 Agent task
 Seed catalog
 PR #846
 Cart totals
 Cursor task
 Add index
 Preview
 search-v2
 CI
 migration-228
 PR #847
 Invoice export
 Claude task
 Backfill data
 Preview
 dashboard-v3
 Agent task
 Seed catalog
 PR #847
 Invoice export
 Claude task
 Backfill data
 Preview
 dashboard-v3
 Agent task
 Seed catalog
 PR #851
 Webhooks
 Preview
 account-settings
 CI
 schema-check
 Copilot task
 Normalize names
 PR #847
 Invoice export
 Claude task
 Backfill data
 Preview
 dashboard-v3
 Agent task
 Seed catalog
 PR #851
 Webhooks
 Preview
 account-settings
 CI
 schema-check
 Copilot task
 Normalize names
 PR #851
 Webhooks
 Preview
 account-settings
 CI
 schema-check
 Copilot task
 Normalize names
 PR #854
 Audit log
 Preview
 pricing-v2
 Agent task
 Optimize query
 PR #857
 Team roles
 PR #851
 Webhooks
 Preview
 account-settings
 CI
 schema-check
 Copilot task
 Normalize names
 PR #854
 Audit log
 Preview
 pricing-v2
 Agent task
 Optimize query
 PR #857
 Team roles
 PR #854
 Audit log
 Preview
 pricing-v2
 Agent task
 Optimize query
 PR #857
 Team roles
 PR #846
 Cart totals
 Cursor task
 Add index
 Preview
 search-v2
 CI
 migration-228
 PR #854
 Audit log
 Preview
 pricing-v2
 Agent task
 Optimize query
 PR #857
 Team roles
 PR #846
 Cart totals
 Cursor task
 Add index
 Preview
 search-v2
 CI
 migration-228
 Production Primary 
 Postgres 18.3 
 Production-like data
 Healthy 99.99% uptime 1,324 branches 
 PR #842
 Add billing
 Full copy ready 2.2s 
 PR #843
 Update schema
 Full copy ready 2.1s 
 PR #842
 Add billing
 Full copy ready 2.2s 
 PR #843
 Update schema
 Full copy ready 2.1s 
 PR #846
 Cart totals
 Cursor task
 Add index
 Preview
 search-v2
 CI
 migration-228
 PR #847
 Invoice export
 Claude task
 Backfill data
 Preview
 dashboard-v3
 Agent task
 Seed catalog
 PR #846
 Cart totals
 Cursor task
 Add index
 Preview
 search-v2
 CI
 migration-228
 PR #847
 Invoice export
 Claude task
 Backfill data
 Preview
 dashboard-v3
 Agent task
 Seed catalog
 PR #847
 Invoice export
 Claude task
 Backfill data
 Preview
 dashboard-v3
 Agent task
 Seed catalog
 PR #851
 Webhooks
 Preview
 account-settings
 CI
 schema-check
 Copilot task
 Normalize names
 PR #847
 Invoice export
 Claude task
 Backfill data
 Preview
 dashboard-v3
 Agent task
 Seed catalog
 PR #851
 Webhooks
 Preview
 account-settings
 CI
 schema-check
 Copilot task
 Normalize names
 Engineering teams use Xata for agentic development
 Agentic development metrics
 Branch creation
 ~3 sec
 Growth in branches created
 5x MoM
 Created by coding agents
 50%
 Branch creation cost
 1,000 for $1
 Modern development needs more than a single staging database.
 Coding agents multiply the number of changes happening at once. A single shared database cannot safely support all those migrations, tests, and experiments.
 Shared staging puts four workflows in one database, causing migration conflicts, failed tests, overwritten data, and waiting. Xata creates four isolated Postgres branches with production-like data so every workflow can run independently without conflicts.
 SHARED STAGING
 SHARED STAGING 
 Shared staging database
 Everyone works in the same database
 Claude — Fix migration
 Migration conflict 
 PR #842 — Add billing
 Tests failing 
 Preview #319 — Checkout
 Test data overwritten 
 PR #845 — Add permissions
 Waiting for database 
 Schema changed while tests were running 
 1 database · 4 workflows · Changes collide 
 Isolated Postgres branches
 Every workflow gets its own branch
 Claude — Fix migration
 Branch ready · 2.1s 
 PR #842 — Add billing
 Tests passed 
 Preview #319 — Checkout
 Preview ready 
 PR #845 — Add permissions
 Running tests 
 4 isolated branches · No conflicts · Created automatically
 Benefits Change schemas safely
 Run migrations and test schema changes without affecting production or anyone else’s work.
 Test with production-like data
 Catch issues that empty databases, fixtures, and mocks cannot reveal before changes ship.
 Work in parallel
 Give every developer, agent, and preview an isolated database without waiting on shared staging.
 Branch any Postgres database in seconds
 Create isolated branches from production without copying the full database. Each branch gets its own schema, compute, and production-like data.
 Copy-on-write storage
 Using copy-on-write storage, each branch shares data with its parent and stores only changes instead of creating full copies.
 Development prod 
 Development / rl/episode-001 
 Development / rl/episode-002 
 Development / sim/load-test 
 Development / sim/regression 
 Scale to zero
 Run branches only when needed. When idle, they hibernate and use no compute.
 280 branches Active: 280 Idle: 0 
 Compute $ 33.60 /hr 
 Wake on the first query
 Branches wake on first query: no connection timeouts, no manual spin-up.
 > SELECT * FROM users LIMIT 3; 
 Production / feature/auth 
 id name email 
 Upstream Postgres
 Branching happens in the storage layer, not through a custom Postgres fork, so you keep standard PostgreSQL, extensions, drivers, and tooling.
 address_standardizer
 address_standardizer_data_us
 amcheck
 auto_explain
 autoinc
 bloom
 btree_gin
 btree_gist
 citext
 cube
 dblink
 dict_int
 dict_xsyn
 earthdistance
 file_fdw
 fuzzystrmatch
 hll
 address_standardizer
 address_standardizer_data_us
 amcheck
 auto_explain
 autoinc
 bloom
 btree_gin
 btree_gist
 citext
 cube
 dblink
 dict_int
 dict_xsyn
 earthdistance
 file_fdw
 fuzzystrmatch
 hll
 address_standardizer
 address_standardizer_data_us
 amcheck
 auto_explain
 autoinc
 bloom
 btree_gin
 btree_gist
 citext
 cube
 dblink
 dict_int
 dict_xsyn
 earthdistance
 file_fdw
 fuzzystrmatch
 hll
 address_standardizer
 address_standardizer_data_us
 amcheck
 auto_explain
 autoinc
 bloom
 btree_gin
 btree_gist
 citext
 cube
 dblink
 dict_int
 dict_xsyn
 earthdistance
 file_fdw
 fuzzystrmatch
 hll
 hstore
 hypopg
 intagg
 intarray
 insert_username
 ip4r
 isn
 lo
 ltree
 moddatetime
 pageinspect
 pg_buffercache
 pg_cron
 pg_freespacemap
 pg_hint_plan
 pg_partman
 pg_prewarm
 hstore
 hypopg
 intagg
 intarray
 insert_username
 ip4r
 isn
 lo
 ltree
 moddatetime
 pageinspect
 pg_buffercache
 pg_cron
 pg_freespacemap
 pg_hint_plan
 pg_partman
 pg_prewarm
 hstore
 hypopg
 intagg
 intarray
 insert_username
 ip4r
 isn
 lo
 ltree
 moddatetime
 pageinspect
 pg_buffercache
 pg_cron
 pg_freespacemap
 pg_hint_plan
 pg_partman
 pg_prewarm
 hstore
 hypopg
 intagg
 intarray
 insert_username
 ip4r
 isn
 lo
 ltree
 moddatetime
 pageinspect
 pg_buffercache
 pg_cron
 pg_freespacemap
 pg_hint_plan
 pg_partman
 pg_prewarm
 pg_repack
 pg_surgery
 pg_trgm
 pg_visibility
 pg_walinspect
 pgrowlocks
 pg_stat_statements
 pg_stattuple
 pgaudit
 pgcrypto
 pgrouting
 pglogical
 pgtap
 plpgsql
 postgres_fdw
 postgis
 postgis_raster
 pg_repack
 pg_surgery
 pg_trgm
 pg_visibility
 pg_walinspect
 pgrowlocks
 pg_stat_statements
 pg_stattuple
 pgaudit
 pgcrypto
 pgrouting
 pglogical
 pgtap
 plpgsql
 postgres_fdw
 postgis
 postgis_raster
 pg_repack
 pg_surgery
 pg_trgm
 pg_visibility
 pg_walinspect
 pgrowlocks
 pg_stat_statements
 pg_stattuple
 pgaudit
 pgcrypto
 pgrouting
 pglogical
 pgtap
 plpgsql
 postgres_fdw
 postgis
 postgis_raster
 pg_repack
 pg_surgery
 pg_trgm
 pg_visibility
 pg_walinspect
 pgrowlocks
 pg_stat_statements
 pg_stattuple
 pgaudit
 pgcrypto
 pgrouting
 pglogical
 pgtap
 plpgsql
 postgres_fdw
 postgis
 postgis_raster
 postgis_sfcgal
 postgis_tiger_geocoder
 postgis_topology
 prefix
 refint
 seg
 sslinfo
 tablefunc
 tcn
 tsm_system_rows
 tsm_system_time
 unaccent
 uuid-ossp
 vector
 wal2json
 xml2
 postgis_sfcgal
 postgis_tiger_geocoder
 postgis_topology
 prefix
 refint
 seg
 sslinfo
 tablefunc
 tcn
 tsm_system_rows
 tsm_system_time
 unaccent
 uuid-ossp
 vector
 wal2json
 xml2
 postgis_sfcgal
 postgis_tiger_geocoder
 postgis_topology
 prefix
 refint
 seg
 sslinfo
 tablefunc
 tcn
 tsm_system_rows
 tsm_system_time
 unaccent
 uuid-ossp
 vector
 wal2json
 xml2
 postgis_sfcgal
 postgis_tiger_geocoder
 postgis_topology
 prefix
 refint
 seg
 sslinfo
 tablefunc
 tcn
 tsm_system_rows
 tsm_system_time
 unaccent
 uuid-ossp
 vector
 wal2json
 xml2
 Automate every branch Created when work starts. Removed when it ends.
 Connect Xata to GitHub, CI, or your coding agents. A Postgres branch is created automatically for every task, pull request, or preview and removed when the work is complete.
 Automated 
 Pull requests
 Create a production-like database branch when a pull request opens. Run migrations and tests against it, then delete it after merge.
 PR #842
 Pull request opened 
 Branch created 
 Tests passed 
 PR #842 : Pull request opened , branch created, Tests passed .
 Automated 
 Coding agents
 Let agents create isolated branches through the API or MCP, safely modify schemas and data, and clean up when the task finishes.
 Claude task
 Code session started 
 Branch created 
 Migration applied 
 Claude task : Code session started , branch created, Migration applied .
 Automated 
 Preview deployments
 Connect every preview to its own Postgres branch so the complete application, code, schema, and data, can be validated before publishing.
 Preview #319
 Preview deployment 
 Branch created 
 Preview live 
 Preview #319 : Preview deployment , branch created, Preview live .
 How to get started Adopt Xata without moving production.
 Keep production where it is, or move it to Xata. Either way, every pull request and deployment preview gets its own isolated Postgres branch.
 Path 01 Keep prod where it is
 Create a clone of your production database in Xata, keep it in sync with production, and have it ready for instant branching.
 Branches from a production clone 
 Production data with built-in anonymization 
 Continuously synced with production 
 Create a production clone 
 Path 02 Run production on Xata
 Run your production database on Xata with native branching, built-in high availability, read replicas, and automatic scale-to-zero.
 Native branches from production 
 High availability 
 Read replicas 
 Create a production database 
 Production-ready Postgres
 Xata runs vanilla PostgreSQL with high-performance storage, isolation, and instant branching built in.
 Xata includes built-in production observability for your database — uptime, query latency, throughput, and active connections.
 xata-dashboard — production 
 All systems operational 
 Last 90 days 
 Uptime 99.99 % 
 p99 Latency 4ms 
 Connections 0 
 Throughput 12.4k qps 
 reads 
 writes 
 Vanilla Postgres
 No forks and no compatibility issues.
 High availability
 Automatic failover to read-replicas.
 PITR backups
 Restore your database to any point in time.
 Premium storage
 Low latency and high throughput storage.
 Example What does a database per pull request cost?
 Consider a company creating 100 pull requests per day against a 100 GB production database. With traditional database infrastructure, giving every pull request its own isolated database quickly becomes unsustainable.
 Traditional Database
 Per database compute
 24 hrs
 Per database storage
 100 GB
 Total compute
 100 × 24 = 2,400 hours 
 Total storage
 100 × 100 GB = 10 TB 
 With Copy-on-Write & Scale-to-Zero
 Per database compute
 ~ 5 min
 Per database storage
 3 GB modified
 Total compute
 100 × 5 min = 9 hours 
 Total storage
 100 GB + (100 × 3 GB) = 400 GB 
 Storage 0.0% less 
 10 TB 
 10 TB 
 400 GB modified 
 400 GB modified 
 Compute 0.0% less 
 2,400 hrs 
 2,400 hrs 
 9 hours 
 9 hours 
 Built for platforms Add branch-native Postgres to your product
 Give every user, workspace, preview, or coding agent an isolated Postgres branch, created through one API and managed by Xata.
 Provision instantly
 Create a new Postgres database in a second through a simple API.
 Branch at any scale
 Create a production-like branch in seconds, regardless of database size. Scale to zero when idle and wake on the next connection.
 Scale to millions
 Support large numbers of short-lived databases without duplicating storage or paying for idle compute.
 Deploy on your terms
 Use Xata Cloud or run in your own cloud with BYOC, private networking, and regional control.
 Explore Xata for platforms 
 What our users are saying
 See what engineers, builders and leaders are saying about Xata.
 Xata is currently the best way to run the pg_duckdb extension in the cloud. The platform’s flexibility and API access make Xata the perfect PostgreSQL partner for us. Jordan Tigani CEO , MotherDuck
 Xata was an easy choice for our team because of how straightforward the entire platform is, while simultaneously providing a suite of adequate features that we need. The Xata team has also been super responsive and more importantly quick to resolve the hiccups that we brought upon ourselves. Chris Windsor Lead Software Engineer , Safestreets
 By adopting Xata, we cut database costs vs. our RDS setup and got better help from Postgres experts. Jignesh Chauhan Co-founder , CallKarma.ai
 Xata was a no-brainer for our team. We get a lot of value out of the copy-on-write database branching and scale-to-zero features. Ben Hubsch Software Engineer , SaaSgrid
 Previous slide Next slide 
 Branch your database in seconds 
 Get started Get in Touch 
 Branch-native Postgres
 Twitter Bluesky LinkedIn YouTube Contact us 
 Product
 Branching Storage Scale-to-Zero BYOC 
 Solutions
 Production CI/CD Agent Sandboxes 
 Resources
 Xata vs Neon Glossary GitHub 
 Developers
 Docs Open Source Status Support 
 Company
 About Blog Careers Brand 
 © Copyright 2026 Xatabase Inc. All Rights Reserved.
 Privacy Policy Security Terms of Use Cookie Settings
