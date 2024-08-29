# example-webapp-with-traefik-and-ssl

This is an example docker compose with traefik, a webapplication and cloudflare based dns validation

Use this ansible playbook to deploy this compose project:
<https://github.com/dtap001/example-webapp-with-traefik-and-ssl-ansible>

- ensure you have set the dns serverat your dns registrator to cloudflare:
  -  https://developers.cloudflare.com/dns/zone-setups/full-setup/setup/
- create cloudflare api token:
  - https://developers.cloudflare.com/fundamentals/api/get-started/create-token/
- create a PAT in github to chechout this  repo or the fork of it on your server
- use that PAT to chechkout either repository
- cp .env.example to .env in the final location of your project
- fill the .env
- while standing inside the folder of the compose file
-   ```
    docker compose up 
    ```
