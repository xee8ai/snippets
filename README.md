# snippets
Stuff I need every then and now and have to search for

## PostgreSQL

On some imports the next auto\_increment ID is not set properly; redefine using the following query

    ALTER SEQUENCE {{TABLENAME}}_id_seq RESTART WITH 1000;

Define search path (for not having to do SELECT * FROM nmsprime.contract)

    SET search_path TO nmsprime,public;
