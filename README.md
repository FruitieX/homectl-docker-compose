# homectl-docker-compose

Example of how to run various homectl services using docker compose.

## Running

- Make sure Docker is installed and running
- If you have a Hue bridge, read through [/hue-mqtt/Settings.toml](/hue-mqtt/Settings.toml) and edit as appropriate.
- If you don't have a Hue bridge, comment out the `hue-mqtt` section in [/docker-compose.yml](/docker-compose.yml)
- Run `docker compose up`
- Navigate to http://localhost:3000
