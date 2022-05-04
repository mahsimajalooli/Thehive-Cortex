# Thehive-Cortex

![cortex-and-thehive-logo](https://user-images.githubusercontent.com/98898685/166641639-036acbdc-7055-4a8d-ab61-beb807bac237.png)

- Run the docker compose template `docker-compose up -d`
- On `http://locahost:9001`, create a Cortex organisation and a user with an API Key
- Copy the API key and set it in `vol/thehive/application.conf` to configure Cortex module
- Restart the docker compose template `docker-compose down && docker-compose up -d`
Use `http://thehive:9000` and `http://cortex:9001` in n8n UI when defining credentials nodes.
default password for Thehive : Username: admin@thehive.local | Password: secret
