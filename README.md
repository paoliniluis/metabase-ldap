# Metabase - LDAP

This is a Docker Compose stack to show how you can configure Metabase with LDAP

## How to run

Just install Docker and do "docker compose up" on the root of the project

# Users

a@b.com / metabot1 is the admin user
then you can configure users in the LDAP server with the LDAP_USERS and LDAP_PASSWORDS env vars

## Tip

In case you need to debug something about the objects inside the LDAP server, use [Apache Directory Studio](https://directory.apache.org/studio/) to connect to the LDAP server in the container (it's exposed through port 1389)