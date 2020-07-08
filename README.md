# CircleCI Orbs

[![license: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

>Repo that contains several orbs for circleci.

## Background

All published orbs can be found here:
https://circleci.com/orbs/registry/?query=t3n&filterBy=all

## Usage

### Orb: Composer

This orb adds a new job to remove composer dev dependencies

| Parameter         | Default value | Description                                                                                         |
| ----------------- | ------------- | --------------------------------------------------------------------------------------------------- |
| workspace_root    | ~/workspace   | Defines the workspace root to operate the commadns in                                               |
| working-directory | app           | The directory the composer commands will be executed in. This dir is relative to the workspace_root |

## Publish

Create a personal API token in [CircleCI](https://app.circleci.com/settings/user/tokens).
Save it to `circleci-cli` config file:

```bash
$ mkdir ~/.circleci
$ cat <<EOF >> ~/.circleci/cli.yml
host: https://circleci.com
endpoint: graphql-unstable
token: <api-token>
EOF
```

Snippets for publishing commands are at [t3n/pet-snippets](https://github.com/t3n/pet-snippets/blob/master/circleci.toml).

## Contributing

PRs accepted.

Small note: If editing the Readme, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

[MIT](LICENSE) t3n - digital pioneers
