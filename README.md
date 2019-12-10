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

## Contributing

PRs accepted.

Small note: If editing the Readme, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

[MIT](LICENSE) t3n - digital pioneers
