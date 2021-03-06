[![Build Status](https://travis-ci.org/ngendah/bawabu.svg?branch=master)](https://travis-ci.org/ngendah/bawabu)
[![Maintainability](https://api.codeclimate.com/v1/badges/51b98d08a31b6234e6d0/maintainability)](https://codeclimate.com/github/ngendah/bawabu/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/51b98d08a31b6234e6d0/test_coverage)](https://codeclimate.com/github/ngendah/bawabu/test_coverage)
[![security](https://hakiri.io/github/ngendah/bawabu/master.svg)](https://hakiri.io/github/ngendah/bawabu/master)

Bawabu 
=======================
A modular and extensible OAuth2 server.

It implements the following grants:
* authorization code with PKCE
* user credentials
* implicit

### Getting Started
Bawabu uses [OpenApi](https://www.openapis.org/) standard for its documentation. This makes it easy to get started.
The only required dependency is [docker-compose](https://docs.docker.com/compose/).
To get started;

1. Clone the project, [bawabu-docker](https://github.com/ngendah/bawabu-docker)

2. Build and run the app,
   ```
    $ docker-compose -f development.yml up
   ```
3. On your browser navigate to `localhost:8080`.
![Alt Text](./docs/pics/oauth2-server.png)

4. Reference documents are available at `docs/auth-code`, `docs/user-cred` and `docs/implicit`.

Seed values for the development server are available [here](./db/seeds.rb)


## OAuth 2.0 Reference
[Framework](https://tools.ietf.org/html/rfc6749)

[Token revocation](https://tools.ietf.org/html/rfc7009)

[Token introspection](https://tools.ietf.org/html/rfc7662)

[Proof key for code exchange (PKCE)](https://tools.ietf.org/html/rfc7636)

[Security considerations](https://tools.ietf.org/html/rfc6819)
