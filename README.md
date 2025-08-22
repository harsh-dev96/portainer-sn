# Mosquitto Pro Single Node

As a first step place your Mosquitto and MQTT Platform license in
`./license`, named `license.lic`.

_Prerequisite:_ Make sure docker and docker compose v2 is installed.

The example setup may simply be started using:

```sh
docker compose up -d
```

To access the logs use the following command from the root folder:

```sh
docker compose logs
```

Open the Platform via <http://localhost:3000/> and setup your user.

The setup depends on a running docker environment and a login to the Cedalo registry.
A more detailed manual can be found here:
<https://docs.cedalo.com/mosquitto/getting-started/onprem/>
