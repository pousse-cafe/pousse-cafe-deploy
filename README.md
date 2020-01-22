# pousse-cafe-deploy

`snapshot_release_settings.xml` provides the required Maven settings for deploying automatically artifacts into SNAPSHOT repository.
It requires 2 environment variables to be defined:

- `USER_ID`
- `USER_PWD`

When using Travis CI, those environment variables have to be provided in the Travis file in the form of [Encrypted Keys](https://docs.travis-ci.com/user/encryption-keys).
