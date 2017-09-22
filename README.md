# Central Authorization Server

This CAS is using a pre-built Ruby app [Casino](https://github.com/rbCAS/CASinoApp) - [Documentation](http://casino.rbcas.com/docs/).

This app is meant to run in a docker container, but relies on other services within other containers. Namely a customized LDAP implementation, and a local mysql backend. The mysql backend is managed by this app, the LDAP service is stand-alone.

TODO: FIX logo size (gets cropped in the login form)

## Requirements
Provide the `cas.yml` config file, so it gets mounted in the container. This build assumes the file will be available in the same directory as the docker files.

