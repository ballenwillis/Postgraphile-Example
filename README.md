# Postgraphile-Example
An example of Postgraphile for my ChicagoJS talk

### Get up and running
1. Create a PostgreSQL database called `forum_example` hosted on your local machine.
2. Run `setup.sql` to generate the schema.
3. Run `data.sql` to fill your database with some fake data. 
4. Run: `postgraphile -c postgres://localhost/forum_example -s forum_example`.
5. Try to break it... I dare ya.
