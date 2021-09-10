## Using The Centifugo Server on windows

Ideally, you want to have this in a folder of it's own and then you will have to run the following command to get it started.

- To generate a config file, which you need before you can start the server.
  `.\centrifugo genconfig`

- To start the server after the config file must have been generated. Run
  `.\centrifugo -c config.json`

- To generate token for a user, from cetrifugo server instead of backend application
  `.\centrifugo gentoken -u Mark`

## The fields in the config file

You can change the allowed_origins option to \* for development and also allow anonymous if you don't have a backend. You will need the api_key for backend interactions.

Any question you might have can be answered on the [documentation page](https://centrifugal.dev/)
