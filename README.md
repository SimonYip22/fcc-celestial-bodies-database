# Celestial Bodies Database

## Overview

This repository contains the `universe.sql` PostgreSQL dump for the freeCodeCamp Relational Database certification project.

The project demonstrates basic relational database design using PostgreSQL, including:

- Table creation
- Primary keys
- Foreign keys
- One-to-many relationships
- `VARCHAR`, `TEXT`, `INT`, `NUMERIC`, and `BOOLEAN` data types
- SQL inserts
- Database export using `pg_dump`

Technical stack includes SQL, PostgreSQL, psql, bash

## Schema Overview

The database models a simple universe structure:

- `galaxy`
- `star`
- `planet`
- `moon`
- `planet_type`

Relationships:

- Stars reference galaxies
- Planets reference stars
- Moons reference planets
- Planets may reference planet types

## File

- `universe.sql` — SQL dump used to recreate the database
