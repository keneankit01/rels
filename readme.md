<h1 align="center">
  Rels
</h1>

<h4 align="center">
  Github release analytics for the console
</h4>

<div align="center">
  <a href="https://github.com/klaussinani/rels">
    <img src="media/header.png" alt="Rels" width="68%">
  </a>
</div>

<p align="center">
  <a href="https://travis-ci.com/klaussinani/rels">
    <img alt="Build Status" src="https://travis-ci.com/klaussinani/rels.svg?branch=master">
  </a>
</p>

## Description

By utilizing a simple and minimal usage syntax rels enables you to easily view various analytics & stats regarding the releases of any GitHub repository, displayed in a clean & concise manner, right from within your terminal.

You can now support the development process through [GitHub Sponsors](https://github.com/sponsors/klaussinani).

Visit the [contributing guidelines](https://github.com/klaussinani/rels/blob/master/contributing.md#translating-documentation) to learn more on how to translate this document into more languages.

Come over to [Twitter](https://twitter.com/klaussinani) to share your thoughts on the project.

## Highlights

- Overall release analytics
- Clean & concise output
- Simple & minimal usage syntax
- Update notifications

## Contents

- [Description](#description)
- [Highlights](#highlights)
- [Install](#install)
- [Usage](#usage)
- [Development](#development)
- [Related](#related)
- [Team](#team)
- [License](#license)

## Install

### Yarn

```bash
yarn global add rels
```

### NPM

```bash
npm install --global rels
```

### Snapcraft

```bash
snap install rels
```

## Usage

```
  Usage
    $ rels [<options> ...]

    Options
      --repo, -r         Repository to get analytics for
      --list, -l         Number of releases to be displayed
      --all, -a          Display all releases
      --help, -h         Display help message
      --version, -v      Display installed version

    Examples
      $ rels --repo klaussinani/tusk
      $ rels --repo klaussinani/tusk --all
      $ rels --repo klaussinani/tusk --list 3
```

## Development

For more info on how to contribute to the project, please read the [contributing guidelines](https://github.com/klaussinani/rels/blob/master/contributing.md).

- Fork the repository and clone it to your machine
- Navigate to your local fork: `cd rels`
- Install the project dependencies: `npm install` or `yarn install`
- Lint the code for errors: `npm test` or `yarn test`

## Related

- [signale](https://github.com/klaussinani/signale) - Highly configurable logging utility
- [qoa](https://github.com/klaussinani/qoa) - Minimal interactive command-line prompts
- [taskbook](https://github.com/klaussinani/taskbook) - Tasks, boards & notes for the command-line habitat
- [hyperocean](https://github.com/klaussinani/hyperocean) - Deep oceanic blue Hyper terminal theme

## Team

- Klaus Sinani [(@klaussinani)](https://github.com/klaussinani)

## License

[MIT](https://github.com/klaussinani/rels/blob/master/license.md)
