+++
title = "Home"
+++

> pgloader loads data into PostgreSQL and allows you to implement
> [Continuous Migration](/white-paper) from your current database to
> PostgreSQL. Read the [White Paper](/white-paper) to learn how to limit
> risks and control your budget, and start your PostgreSQL migration today!

<h1 style="border-bottom: 1px solid black; margin-top: 2em; text-align: right;">
  Introduction
</h1>

<figure style="float: left; clear: right; display: block; width: 200px; margin-right: 1em;">
    <img width="200px" src="/img/logo.png">
</figure>

pgLoader has two modes of operation. It can either load data from files,
such as CSV or Fixed-File Format; or migrate a whole database to PostgreSQL.
  
pgLoader supports several RDBMS solutions as a migration source, and fetches
information from the catalog tables over a connection to then create an
equivalent schema in PostgreSQL. This means that you can [migrate to
PostgreSQL in a single command-line](/about/)!

Supported operations include:

  - Migrate from MySQL to PostgreSQL
  - Migrate from SQLite to PostgreSQL
  - Migrate from MS SQL Server® to PostgreSQL

You can also _migrate from database files_ in the DBF and IXF formats, where
pgLoader can inspect the target table format for you automatically in the
file headers.

<h1 style="border-bottom: 1px solid black; margin-top: 2em; text-align: right;">
  Migrating to PostgreSQL: the White Paper
</h1>

<figure style="float: left; clear: right; display: block; width: 200px; margin-right: 1em;">
    <a href="/white-paper/">
        <img style="width:200px; height: 229px; border: 1px solid lightblue; box-shadow: 15px 0 20px -20px lightblue, -15px 0 20px -20px lightblue;"
               src="/img/MigratingToPostgreSQL-Cover.png">
    </a>
</figure>

The [White Paper](/white-paper/) titled “Migrating to PostgreSQL, Tools and
Methodology” explains the idea of [Continuous
Migration](/blog/continuous-migration/). The paper also covers migration
projects budget decisions and risks mitigation. It's free and contains all
you need to get started, including a PostgreSQL Architecture primer!

<h1 style="border-bottom: 1px solid black; margin-top: 3em; text-align: right;">
  pgLoader documentation
</h1>

<figure style="float: right; clean: left; display: block; width: 200px;">
  <a href="http://pgloader.readthedocs.io/en/latest/">
    <img width="200px" src="/img/doc-20-512.png">
  </a>
</figure>

Looking for pgloader's *documentation*? It is now hosted at
<http://pgloader.readthedocs.io/en/latest/>.

It contains a tutorial for the many different source types supported, code
samples, simple and complex load files and command line examples, and a full
reference of every option available.

<h1 style="border-bottom: 1px solid black; margin-top: 2em; text-align: right;">
  Sustainable Open Source Development
</h1>

<div style="float: left; clear: right; margin: 2em;">
 <a class="btn" href="https://gum.co/CjXn" target="_blank">
    Become a pgloader Patron!
 </a> 
</div>

Have a look at the [RoadMap](/roadmap) and contribute to it either by
sending a *Pull Requests* to the project, or becoming a **pgloader Patron**.

