# Awesome Postgres [![awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome PostgreSQL software, libraries, tools and resources, forked from dhamaniasad/awesome-postgres

## Contents
- [Documentation](#documentation)
- [Management Tools](#management-tools)
- [GUI](#gui)
- [Distributions and Server](#distributions-and-server)
- [Monitoring](#monitoring)
- [High-Availability](#high-availability)
- [Backups](#backups)
- [Optimization](#optimization)
- [Utilities](#utilities)
- [CLI](#cli)
- [Extensions](#extensions)
- [Migration tools](#migration-tools)
- [Language bindings](#language-bindings)
- [Tutorials](#tutorials)
- [Blogs](#blogs)
- [Articles](#articles)
- [Newsletters](#newsletters)
- [PaaS (PostgreSQL as a Service)](#paas-postgresql-as-a-service)
- [Professional Support](#professional-support)
- [Who use PostgreSQL?](#who-use-postgresql)
- [PostgreSQL Forks](#postgresql-forks)
- [PostgreSQL Code Contribution](#postgresql-code-contribution)


Contributing
=======================================================================

Contributions are most welcome!

This list is just getting started, please contribute to make it super awesome.

Check out the [Contributing Guidelines](https://github.com/pg-tr/awesome-postgres/blob/master/CONTRIBUTING.md).

### Documentation
* [PostgreSQL Documentation](https://www.postgresql.org/docs/) - PostgreSQL Official Documentation
* [Parameters Documentation](https://postgresqlco.nf/) - All the documentation and help you need about all the postgresql.conf parameters.
* [pgPedia](https://pgpedia.info/) - An encyclopedia (work-in-progress) of things PostgreSQL-related. And some hacks.

### Management Tools
* [Temboard](https://temboard.readthedocs.io/) - temBoard is a powerful management tool for PostgreSQL. You can use it to monitor, optimize or configure multiple PostgreSQL instances.
* [Elephant Shed](https://elephant-shed.io/) - PostgreSQL and everything that goes with it, from backup to monitoring and reporting.
### High-Availability
* [BDR](https://github.com/2ndQuadrant/bdr) - BiDirectional Replication - a multimaster replication system for PostgreSQL
* [Patroni](https://github.com/zalando/patroni) - Template for PostgreSQL HA with ZooKeeper or etcd.
* [Stolon](https://github.com/sorintlab/stolon) - PostgreSQL HA based on Consul or etcd, with Kubernetes integration.
* [pglookout](https://github.com/ohmu/pglookout) - Replication monitoring and failover daemon.
* [repmgr](https://github.com/2ndQuadrant/repmgr) - Open-source tool suite to manage replication and failover in a cluster of PostgreSQL servers.
* [Slony-I](http://slony.info) - "Master to multiple slaves" replication system with cascading and failover.
* [PAF](http://dalibo.github.io/PAF/) - PostgreSQL Automatic Failover High-Availibility for Postgres, based on Pacemaker and Corosync.
* [Governer](https://github.com/compose/governor) - Runners to orchestrate a high-availability PostgreSQL.
* [pg_auto_failover](https://github.com/citusdata/pg_auto_failover) - Postgres extension and service for automated failover and high-availability.

### Backups
* [Barman](http://www.pgbarman.org/) - Backup and Recovery Manager for PostgreSQL by 2ndQuadrant.
* [OmniPITR](https://github.com/omniti-labs/omnipitr) - Advanced WAL File Management Tools for PostgreSQL.
* [pg_probackup](https://github.com/postgrespro/pg_probackup) – A fork of pg_arman, improved by @PostgresPro, supports incremental backups, backups from replica, multithreaded backup and restore, and anonymous backup without archive command.
* [pgBackRest](http://www.pgbackrest.org) - Reliable PostgreSQL Backup & Restore.
* [pghoard](https://github.com/ohmu/pghoard) - Backup and restore tool for cloud object stores (AWS S3, Azure, Google Cloud, OpenStack Swift).
* [wal-e](https://github.com/wal-e/wal-e) - Simple Continuous Archiving for PostgreSQL to S3, Azure, or Swift by Heroku.

### GUI
* [Adminer](https://www.adminer.org/) - Full-featured database management tool written in PHP.
* [DataGrip](https://www.jetbrains.com/datagrip/) - IDE with advanced tool sets and good cross-platform experience (Commercial Software).
* [Datazenit](https://datazenit.com/) - Web-based PostgreSQL GUI (Commercial Software).
* [DBeaver](http://dbeaver.jkiss.org) - Universal Database Manager with excellent support for PostgreSQL.
* [dbglass](http://dbglass.web-pal.com) - Cross-platform desktop client for PostgreSQL, built with Electron.
* [JackDB](https://www.jackdb.com/) - Web-based SQL query interface (Commercial Software).
* [Metabase](http://www.metabase.com) - Simple dashboards, charts and query tool for PostgreSQL.
* [pgAdmin](https://www.pgadmin.org/) - PostgreSQL Administration and Management GUI.
* [pgModeler](http://pgmodeler.com.br/) - pgModeler is an open-source PostgreSQL Database Modeler.
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser written in Go.
* [phpPgAdmin](https://github.com/phppgadmin/phppgadmin) - The Premier Web Based Administration Tool for PostgreSQL.
* [Postbird](https://github.com/Paxa/postbird) - PostgreSQL Client for macOS.
* [Postico](https://eggerapps.at/postico/) - Modern PostgreSQL Client for macOS (Commercial Software).
* [PSequel](http://www.psequel.com/) - Clean and simple interface to perform common PostgreSQL tasks quickly (Commercial Software).
* [SQL Tabs](http://www.sqltabs.com/) - Cross Platform Desktop Client for PostgreSQL written in JS.
* [SQLPro for Postgres](http://macpostgresclient.com/) - Simple, powerful PostgreSQL manager for macOS (Commercial Software).
* [Warp](http://warp.one/) - macOS desktop tool for by-example querying and data transfer from/to PostgreSQL (Commercial Software).
* [HeidiSQL](https://www.heidisql.com/) - HeidiSQL is a useful and reliable tool designed for web developers using the popular MySQL server, Microsoft SQL databases and PostgreSQL.
* [PostgreSQL Management Tool VS Code Extension](https://github.com/Borvik/vscode-postgres) - PostgreSQL extension for vscode providing explorer, highlighting, diagnostics, and intellisense by Borvik
* [PostgreSQL VS Code Extension by Microsoft](https://github.com/Microsoft/vscode-postgresql) - PostgreSQL extension for VSCODE by Microsoft

### Distributions and Server
* [Postgres.app](http://postgresapp.com/) - The Easiest Way to Get Started with PostgreSQL on macOS.
* [Postgresql Installers](https://www.bigsql.org/postgresql/installers.jsp) - Downloadable binaries tested to run on Centos 6+, Ubuntu 12.04+, OSX 10.9+, Windows 7+ and Windows Server 2008+.
* [Postgresql Installers](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads) - Download the installer certified by EnterpriseDB for all supported PostgreSQL versions.
* [Postgres-XL](http://www.postgres-xl.org/) - Scalable Open Source PostgreSQL-based Database Cluster.
* [Citus](https://github.com/citusdata/citus) - Scalable PostgreSQL cluster for real-time workloads.
* [Greenplum Database](http://greenplum.org/) - The World's First Open Source Massively Parallel Data Warehouse.
* [PipelineDB](https://www.pipelinedb.com/) - The Streaming SQL Database.
* [BigSQL](https://www.bigsql.org/) -  Postgresql by BigSQL. The most complete and developer-friendly distribution of the world's most advanced open source database.

### CLI
* [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting
* [psql](https://www.postgresql.org/docs/current/static/app-psql.html) - The built-in PostgreSQL CLI client
* [psql2csv](https://github.com/fphilipe/psql2csv) - Run a query in psql and output the result as CSV

### Monitoring
* [check\_pgactivity](https://github.com/OPMDG/check_pgactivity) - check\_pgactivity is designed to monitor PostgreSQL clusters from Nagios. It offers many options to measure and monitor useful performance metrics.
* [Check\_postgres](https://github.com/bucardo/check_postgres) - Nagios check\_postgres plugin for checking status of PostgreSQL databases.
* [libzbxpgsql](https://github.com/cavaliercoder/libzbxpgsql) - Comprehensive PostgreSQL monitoring module for Zabbix.
* [mamonsu](https://github.com/postgrespro/mamonsu) - PostgreSQL Monitoring agent for zabbix. Also it can be used as report, tune and cli.
* [Pome](https://github.com/rach/pome) - Pome stands for PostgreSQL Metrics. Pome is a PostgreSQL Metrics Dashboard to keep track of the health of your database.
* [pg\_view](https://github.com/zalando/pg_view) - Open-source command-line tool that shows global system stats, per-partition information, memory stats and other information.
* [pgbench](https://www.postgresql.org/docs/devel/static/pgbench.html) - Run a benchmark test on PostgreSQL.
* [zabbix](https://www.zabbix.com/integrations/postgresql#tab:official2) - Zabbix Template for PostgreSQL Agent 2
* [pg_bloat_check](https://github.com/keithf4/pg_bloat_check) - Provides a bloat report for PostgreSQL tables and/or indexes
* [prometheus-pgbouncer-exporter](https://github.com/spreaker/prometheus-pgbouncer-exporter) -  Prometheus exporter for PgBouncer

### Extensions
* [cstore\_fdw](https://github.com/citusdata/cstore_fdw) - Columnar store for analytics with PostgreSQL.
* [cyanaudit](http://pgxn.org/dist/cyanaudit/) - Cyan Audit provides in-database logging of all DML activity on a column-by-column basis.
* [pglogical](https://github.com/2ndQuadrant/pglogical) - Extension that provides logical streaming replication.
* [pg\_partman](https://github.com/keithf4/pg_partman) - Partition management extension for PostgreSQL.
* [pg\_paxos](https://github.com/citusdata/pg_paxos/) - Basic implementation of Paxos and Paxos-based table replication for a cluster of PostgreSQL nodes.
* [pg\_shard](https://github.com/citusdata/pg_shard) - Extension to scale out real-time reads and writes.***deprecated***
* [PGStrom](https://wiki.postgresql.org/wiki/PGStrom) - Extension to offload CPU intensive workloads to GPU.
* [pgxn](http://pgxn.org/) PostgreSQL Extension Network - central distribution point for many open-source PostgreSQL extensions
* [plpgsql\_check](https://github.com/okbob/plpgsql_check) - Extension that allows to check plpgsql source code.
* [PostGIS](http://postgis.net/) - Spatial and Geographic objects for PostgreSQL.
* [PG_Themis](https://github.com/cossacklabs/pg_themis) - Postgres binding as extension for crypto library Themis, providing various security services on PgSQL's side.
* [zomboDB](https://github.com/zombodb/zombodb) - Extension that enables efficient full-text searching via the use of indexes backed by Elasticsearch.
* [pgpyml](https://github.com/Minoro/pgpyml) - (WIP) Use machine learning models written in Python inside PostgreSQL.
* [Transparent Data Encryption](https://www.cybertec-postgresql.com/en/products/postgresql-transparent-data-encryption/) - Transparent Data Encryption (TDE) is a CYBERTEC patch to PostgreSQL.

### Migration Tools
* [Babelfish](https://babelfishpg.org/) - With Babelfish, applications that currently running on SQL Server can now run directly on PostgreSQL with fewer code changes.
* [sqlserver2pgsql](https://github.com/dalibo/sqlserver2pgsql) - Migration tool to convert a Microsoft SQL Server Database into a PostgreSQL database, as automatically as possible.
* [db2topg](https://github.com/dalibo/db2topg) - Automated tool for DB2 migration to PostgreSQL, ala ora2pg.
* [pgtsql](https://bitbucket.org/openscg/pgtsql) - Extension that provides a PostgreSQL procedural language that implements the Transact-SQL language.
* [ora2pg](http://ora2pg.darold.net/) - Moves Oracle and MySQL database to PostgreSQL.
* [pgloader](https://pgloader.io/) - Migration Tool to PostgreSQ from MySQL, SQLite, MS SQL Server®.

### Optimization
* [PgHero](https://github.com/ankane/pghero) - PostgreSQL insights made easy.
* [pgtune](https://github.com/gregs1104/pgtune/) - PostgreSQL configuration wizard.
* [pgconfig.org](https://www.pgconfig.org/) - PostgreSQL Online Configuration Tool (also based on pgtune).
* [PoWA](http://dalibo.github.io/powa/) - PostgreSQL Workload Analyzer gathers performance stats and provides real-time charts and graphs to help monitor and tune your PostgreSQL servers.
* [Dalibo Explain Visualizer](https://explain.dalibo.com) - This service lets you analyze, visualize and share Postgres Query Plans. It will compute and highlight the most important information to make them easier to understand.
* [Tatiyants Explain Visualizer](http://tatiyants.com/pev/#/plans) - Postgres Explain Visualizer (dev) is designed to make EXPLAIN output easier to grok. It creates a graphical representation of the plan.
* [Depez Explain Visualizer](https://explain.depesz.com) - PostgreSQL's explain analyze made readable
* [AwesomeExplain](https://github.com/sandboxws/awesome_explain) - AwesomeExplain provides the same APM level of query analysis under your development and test Rails environments.


### Utilities
* [apgdiff](http://www.apgdiff.com/) - Compares two database dump files and creates output with DDL statements that can be used to update old database schema to new one.
* [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - ERAlchemy generates Entity Relation (ER) diagram from databases.
* [mysql-postgresql-converter](https://github.com/lanyrd/mysql-postgresql-converter) - Lanyrd's MySQL to PostgreSQL conversion script.
* [ora2pg](http://ora2pg.darold.net) - Perl module to export an Oracle database schema to a PostgreSQL compatible schema.
* [pg\_activity](https://github.com/julmon/pg_activity) - top like application for PostgreSQL server activity monitoring.
* [pganalyze](https://pganalyze.com) - PostgreSQL Performance Monitoring (Commercial Software).
* [pgbadger](https://github.com/dalibo/pgbadger) - Fast PostgreSQL Log Analyzer.
* [PgBouncer](http://pgbouncer.github.io) - Lightweight connection pooler for PostgreSQL.
* [pgCenter](https://github.com/lesovsky/pgcenter) - Provides convenient interface to various statistics, management task, reloading services, viewing log files and canceling or terminating database backends.
* [pgclimb](https://github.com/lukasmartinelli/pgclimb) - Export data from PostgreSQL into different data formats.
* [pgfutter](https://github.com/lukasmartinelli/pgfutter) - Import CSV and JSON into PostgreSQL the easy way.
* [PGInsight](http://pginsight.io/) - CLI tool to easily dig deep inside your PostgreSQL database.
* [pgloader](https://github.com/dimitri/pgloader) - Loads data into PostgreSQL using the COPY streaming protocol, and does so with separate threads for reading and writing data.
* [pgpool-II](http://www.pgpool.net/mediawiki/index.php/Main_Page) - Middleware that provides connection pooling, replication, load balancing and limiting exceeding connections.
* [pgsync](https://github.com/ankane/pgsync) - Tool to sync PostgreSQL data to your local machine.
* [PGXN client](https://github.com/dvarrazzo/pgxnclient) - Command line tool to interact with the PostgreSQL Extension Network
* [postgresql-metrics](https://github.com/spotify/postgresql-metrics) - Tool that extracts and provides metrics for your PostgreSQL database.
* [PostgREST](https://github.com/begriffs/postgrest) - Serves a fully RESTful API from any existing PostgreSQL database.
* [yoke](https://github.com/nanopack/yoke) - PostgreSQL high-availability cluster with auto-failover and automated cluster recovery.
* [pglistend](https://github.com/kabirbaidhya/pglistend) - A lightweight PostgresSQL `LISTEN`/`NOTIFY` daemon built on top of `node-postgres`.
* [ZSON](https://github.com/afiskon/zson) - PostgreSQL extension for transparent JSONB compression
* [pg_chameleon](https://github.com/the4thdoctor/pg_chameleon) - MySQL to PostgreSQL replication system.
* [pg-ldap-sync](https://github.com/larskanis/pg-ldap-sync) - Use LDAP permissions in PostgreSQL
* [pgagroal](https://agroal.github.io/pgagroal/) -  High-performance connection pool for PostgreSQL
* [odyssey](https://github.com/yandex/odyssey) - Scalable PostgreSQL connection pooler

### Language bindings
* Common Lisp: [Postmodern](https://github.com/marijnh/Postmodern)
* Elixir: [postgrex](https://github.com/elixir-ecto/postgrex)
* Go: [pgx](https://github.com/jackc/pgx)
* Java: [PostgreSQL JDBC Driver](https://jdbc.postgresql.org/)
* Node: [node-postgres](https://github.com/brianc/node-postgres), [pg-promise](https://github.com/vitaly-t/pg-promise)
* Perl: [DBD-Pg](http://search.cpan.org/~turnstep/DBD-Pg/Pg.pm)
* PHP: [Pomm](http://www.pomm-project.org), [pecl/pq](https://github.com/m6w6/ext-pq)
* Python: [psycopg2](https://pypi.python.org/pypi/psycopg2)
* Ruby: [pg](https://bitbucket.org/ged/ruby-pg/wiki/Home)
* Rust: [rust-postgresql](https://github.com/sfackler/rust-postgres)

### Tutorials
* [The Internals of PostgreSQL](http://www.interdb.jp/pg/) - for database administrators and system developers
* [Backup and recover a PostgreSQL DB using wal-e](https://coderwall.com/p/cwe2_a/backup-and-recover-a-postgres-db-using-wal-e) - Tutorial about setting up continuous archiving in PostgreSQL using wal-e.
* [PG Casts](https://www.pgcasts.com) - Free weekly PostgreSQL screencasts by Hashrocket.
* [Postgres Guide](http://postgresguide.com/) - Guide designed as an aid for beginners and experienced users to find specific tips and explore tools available within PostgreSQL.
* [PostgreSQL Exercises](https://pgexercises.com/) - Site  to make it easy to learn PostgreSQL by doing exercises.
* [tutorialspoint PostgreSQL tutorial](http://www.tutorialspoint.com/postgresql/) - Very extensive collection of tutorials on PostgreSQL
* [PostgreSQL configuration for humans](https://postgresqlco.nf/en/doc/param/)
* [Katacoda Scenarios](https://www.katacoda.com/search?q=postgresql&hPP=12&idx=scenarios&p=0&is_v=1) - Several hands-on scenarios
* [PgPedia](https://pgpedia.info/index.html) - An encyclopedia (work-in-progress) of things PostgreSQL-related. And some hacks.

### Blogs
* [Planet PostgreSQL](https://planet.postgresql.org/) - Blog aggregation service for PostgreSQL.
* [Andrew Dunstan's PostgreSQL and Technical blog](http://adpgtech.blogspot.ru/search/label/PostgreSQL/)
* [Bruce Momjian's PostgreSQL blog](http://momjian.us/main/blogs/pgblog.html)
* [Craig Kerstiens PostgreSQL posts](http://www.craigkerstiens.com/categories/postgres/) - Set of posts on PostgreSQL cool features, tips and tricks.
* [Database Soup](http://www.databasesoup.com/search/label/postgresql/) - Josh Berkus' blog.
* [Michael Paquier's blog](http://paquier.xyz/)
* [Robert Haas' blog](http://rhaas.blogspot.ru/search/label/postgresql/)
* [select * from depesz;](https://www.depesz.com/tag/postgresql/) - Hubert Lubaczewski's blog.
* [Revolution Systems](http://www.revsys.com/blog/tags/postgresql/) - We are performance tuners, Django and PostgreSQL experts, infrastructure and scaling architects.
* [OnGress | Blog](https://ongres.com/blog/) - As the name says, the core of our business is Postgres databases.
* [Severalnines Database Blog](https://severalnines.com/database-blog)
* [Percona Blog](https://www.percona.com/blog/category/postgresql/)
* [Cybertec Blog](https://www.cybertec-postgresql.com/en/blog/) - Get the newest tricks and useful tips about the world of PostgreSQL and Data Science! Our authors and technicians share their knowledge to keep you going with your data.
* [PostgresPro Blog](https://postgrespro.com/blog) - Postgrespro PostgreSQL company Blog
* [PostgresPro Blog in Habr.com](https://habr.com/en/company/postgrespro/) - Postgrespro PostgreSQL company Blog in habr.com
* [Crunchydata Blog](https://blog.crunchydata.com/blog) - Crunchydata company Blog
* [Data Egret](https://dataegret.com/news-blog/) Data Egret News & Blog
* [MigOps](https://www.migops.com/blog/) - Postgres Migration Expertise Company Blog

### Articles
* [What PostgreSQL has over other open source SQL databases: Part I](https://www.compose.com/articles/what-postgresql-has-over-other-open-source-sql-databases/)
* [Debugging PostgreSQL performance, the hard way](https://www.justwatch.com/blog/post/debugging-postgresql-performance-the-hard-way/)
* [SQL Server vs MySQL vs PostgreSQL Delete Performance Comparison](https://www.mssqltips.com/sqlservertip/6607/delete-sql-performance-for-sql-server-mysql-and-postgresql/)

### Newsletters
* [Postgres Weekly](http://postgresweekly.com/) - Weekly newsletter that contains articles, news, and repos relevant to PostgreSQL.

### PaaS *(PostgreSQL as a Service)*
* [Aiven PostgreSQL](https://aiven.io/postgresql) - PostgreSQL as a service in AWS, Azure, DigitalOcean, Google Cloud and UpCloud; plans range from $19/month single node instances to large highly-available setups, free trial for two weeks.
* [Citus Cloud](https://www.citusdata.com/product/cloud) - Production grade scaled out PostgreSQL as a service enabling real-time workloads and sharding your multi-tenant apps.
* [Database Labs](https://www.databaselabs.io) - Get a production-ready cloud PostgreSQL server in minutes, from $20 a month Backups, monitoring, patches, and 24/7 tech support all included.
* [ElephantSQL](https://www.elephantsql.com/) - Offers databases ranging from shared servers for smaller projects and proof of concepts, up to enterprise grade multi server setups. Has free plan for up to 5 DBs, 20 MB each.
* [Heroku Postgres](https://elements.heroku.com/addons/heroku-postgresql) - Plans from free to huge, operated by PostgreSQL experts. Does not require running your app on Heroku. Free plan includes 10,000 rows, 20 connections, up to two backups, and has PostGIS support.
* [Azure Postgres](https://azure.microsoft.com/en-us/services/postgresql/) - Azure Database for PostgreSQL
[Amazon RDS for PostgreSQL](https://aws.amazon.com/rds/postgresql/)
[Google Cloud SQL](https://cloud.google.com/sql#section-9)


### Professional Support
* [Complete List](https://www.postgresql.org/support/professional_support/)

### Who Use PostgreSQL?
* [EnterpriseDB Customers](https://www.enterprisedb.com)
* [Cybertech](https://www.cybertec-postgresql.com/en/postgresql-overview/solutions-who-uses-postgresql/)
* [2ndQuadrant](https://www.2ndquadrant.com/en/postgresql/who-uses-postgresql/)
* [Learn PostgreSQL](https://github.com/dwyl/learn-postgresql/issues/31)

### PostgreSQL Forks
* [PostgreSQL Derivative Databases](https://wiki.postgresql.org/wiki/PostgreSQL_derived_databases)

### PostgreSQL Code Contribution

* [PostgreSQL Git Organization](https://git.postgresql.org/gitweb/)
* [Submitting a Patch](https://wiki.postgresql.org/wiki/Submitting_a_Patch)

