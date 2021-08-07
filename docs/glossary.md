# Glossary

## CLI

The CloudQuery CLI (Command-line Interface) is the core [open-source](https://github.com/cloudquery/cloudquery) project that expects to be run on your local machine as CLI or on a remote machine.

## SDK

The [CloudQuery SDK](https://github.com/cloudquery/cq-provider-sdk) is the open-source SDK library used by official and community providers to integrate with CloudQuery Eco-System. The SDK makes it easy to write new providers and takes care of the TL in ETL (Extract-Transform-Load).

## Fetch

Fetch is the both the CLI command and the process when CloudQuery extracts all the configured resources in `config.hcl`, transforms them and loads them into the database.

## Policy

CloudQuery Policy that written with HCL as the logic layer and SQL as the query layer.

## Query

SQL Query, usually targeting the CloudQuery database.

## Provider

CloudQuery Provider is a plugin responsible to extract information/configuration from a specific Cloud Infrastructure Provider SaaS application or literraly anything else that is accessible via API (Rest, GRPC, GraphQL).

Currently all providers are listed in https://hub.cloudquery.io

Developing new provider

## HCL

[HashiCorp Configuration Language](https://github.com/hashicorp/hcl) which is used by CloudQuery to write configuration and policies.

## Resource

The fetch command is working on a list of resources defined in each provider (in `config.hcl`).

For example `ec2_instances` is a resource in `aws` provider.