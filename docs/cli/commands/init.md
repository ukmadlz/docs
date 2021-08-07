# init

Generate initial config.hcl for fetch command

## Usage
`cloudquery init [choose one or more providers (aws,gcp,azure,okta,...)] [flags]`

## Examples

```bash
# Downloads aws provider and generates config.hcl for aws provider
cloudquery init aws

# Downloads aws,gcp providers and generates one config.hcl with both providers
cloudquery init aws gcp
```

## Additional help topics
```
Use "cloudquery init options" for a list of global CLI options.
```