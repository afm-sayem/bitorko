# Bitorko

[![Join the chat at https://gitter.im/afm-sayem/bitorko](https://badges.gitter.im/afm-sayem/bitorko.svg)](https://gitter.im/afm-sayem/bitorko?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Bitorko (বিতর্ক) is the end to end debate tournament organization and community management platform for Bangladeshi debating community.

## Technical specifications:

The projects client(frontend) is built on [Aurelia](http://aurelia.io). The server component is running on [expressJS](http://expressjs.com/) with [PostgreSQL](http://postgresql.org) as the database.

To run the project:
- Install nodeJS > 5.x (we recommend using [nvm](https://github.com/creationix/nvm))
- Run PostgreSQL server
- Create a database called `bitorko-dev`(or anything you like)
- Change the database connection information in `server/config/development` if necessary
- From `server` directory, run `gulp watch`
- Go to `http://localhost:3000`

We are actively seeking contributors(both technical and non-technical) so please reach out to info@bitorko.org if you can help with any existing [issues](https://github.com/afm-sayem/bitorko/issues).
