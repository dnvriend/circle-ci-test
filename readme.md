# circle-ci-test
[![CircleCI](https://circleci.com/gh/dnvriend/akka-persistence-inmemory/tree/master.svg?style=svg)](https://circleci.com/gh/dnvriend/akka-persistence-inmemory/tree/master)

A small study project on how to configure circle ci with tag/branch commit and behavior

## Installing Local-CLI
Type the following:

```bash
$ curl https://raw.githubusercontent.com/CircleCI-Public/circleci-cli/master/install.sh \
	--fail --show-error | bash
```

## Configuring the Local-CLI
You need to [generate a personal API token in the CircleCI portal](https://circleci.com/docs/2.0/local-cli/#configuring-the-cli)

## Validating your config
Type the following:

```bash
$ circleci config validate
```

## Testing your build locally
To run your build locally for test type the following:

```bash
$ circleci local execute --branch master
```

Limitations are that you cannot run a build for a tag.

## Resources
- [Circle CI - Workflow executions](https://circleci.com/docs/2.0/workflows/)
- [Circle CI - Environment Variables](https://circleci.com/docs/2.0/env-vars/#built-in-environment-variables)
- [Circle CI - Local CLI](https://circleci.com/docs/2.0/local-cli/)
