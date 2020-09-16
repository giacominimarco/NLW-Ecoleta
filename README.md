# NLW-Ecoleta
  Application that will help you locate collection points for recycling.

# Prerequisites

  Have Node.js installed on the machine;
  Have a package manager, NPM or Yarn;
  Have the Expo installed globally on the machine;

Start Aplication:
  # Create the database
    $ cd server
    $ yarn knex:migrate
    $ yarn knex:seed

  # Start the server
    $ cd server
    $ yarn
    $ yarn dev

  # Start the web
    $ cd web
    $ yarn
    $ yarn start

  # Start the mobile
    $ cd mobile
    $ yarn
    $ yarn start
