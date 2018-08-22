# Postgraphile-Example
An example of Postgraphile for my ChicagoJS talk

To run, simply run `setup.sql` to generate the schema followed by `data.sql` to fill it with some fake data. Then, from the terminal, run: `postgraphile -c postgres://localhost/forum_example -s forum_example` and you will have a fully functional GraphQL API set up.
