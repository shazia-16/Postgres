# PostgreSQL Schemas & SQL Practice

A collection of relational database schemas, entity-relationship diagrams (DBML), and SQL query exercises built for PostgreSQL.

## Repository Structure

* **`Coding Exercises/`** — Targeted SQL practice problems (`Coding Exercise 1.sql` – `Coding Exercise 24.sql`) covering filtering, aggregations, joins, subqueries, and window functions.
* **`Comments/`** — Schema design for a social media commenting system supporting nested/threaded replies, edit/delete flags, and composite indexing.
  * `comments.dbml` — Database Markup Language (DBML) definition.
  * `Comments Schema.sql` — PostgreSQL DDL script for table creation and constraints.
  * `comments.png` — Visual Entity-Relationship Diagram (ERD).
* **`Instagram application/`** — Relational database schema modeling core Instagram features (users, posts, likes, followers, comments, and hashtags).
  * `ERDiagram.sql` — Schema diagram definition script.
  * `IG table creation.sql` — PostgreSQL DDL script for creating the application tables and relationships.
  * `ER.png` — Visual Entity-Relationship Diagram (ERD).
* **`SECTION1 SQL Statement.sql` – `SECTION 14 SQL Statement.sql`** — Structured SQL query scripts organized by core relational database concepts.

## How to Run

1. Ensure **PostgreSQL** is installed and running locally (or use a cloud PostgreSQL instance such as Supabase).
2. Create a new database:
   ```sql
   CREATE DATABASE postgres_practice;