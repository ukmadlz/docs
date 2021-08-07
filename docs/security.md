# Security

This section will list key security points you need to make sure you follow best-practices if you decide to "host it yourself"

## Security Provider Authentication Credentials

* Provider Authentication Credentials should always be read-only.
* The machine where cloudquery is running should be secured with the correct permissions as it contains the credentials to your cloud-infrastructure.

## Security CloudQuery Database

Even though the CloudQuery database contains only configuration and meta-data you should protect it and keep it secure with correct access & permissions.