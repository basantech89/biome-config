# @awesome-tools/biome
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

### NX. plugin for Biome for multi-repo or mono-repo projects. Feel free to use this package.

[![CI](https://github.com/basantech89/biome-config/actions/workflows/main.yml/badge.svg)](https://github.com/basantech89/biome-config/actions/workflows/main.yml)
[![License: Apache 2](https://img.shields.io/badge/License-Apache2-blue.svg)](https://opensource.org/license/apache-2-0)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Code of Conduct](https://img.shields.io/badge/code-of%20conduct-green.svg)](https://publiclab.org/conduct)

## Table of Contents

- [@awesome-tools/biome](#awesome-toolsbiome)
    - [NX. plugin for Biome for multi-repo or mono-repo projects. Feel free to use this package.](#nx-plugin-for-biome-for-multi-repo-or-mono-repo-projects-feel-free-to-use-this-package)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
    - [Things to know](#things-to-know)
  - [Issues](#issues)
    - [🐛 Bugs](#-bugs)
    - [💡 Feature Requests](#-feature-requests)
  - [LICENSE](#license)
  - [NX Biome Plugin](#nx-biome-plugin)
  - [Building](#building)
  - [Contributors ✨](#contributors-)

## Installation

This module is distributed via [npm](https://www.npmjs.com/) which is bundled with [node](https://nodejs.org/) and
should be installed as one of your project's `devDependencies`:

```
npm install --save-dev @awesome-tools/biome
```

## Usage

Add a biome.json to your project root with the following content:

```json5
{
	"extends": ["@awesome-tools/biome/config"]
}
```

Then prepend this plugin to your `nx.json`:

```json5
{
  "plugins": [
    "@awesome-tools/biome",
    // other plugins...
  ]
}
```

You can now lint your projects with biome using Nx:
```shell
nx lint <project-name>
```

### Things to know

This project is meant to be used with [Nx](https://nx.dev).

## Issues

_Looking to contribute? Look for the [Good First Issue](https://github.com/basantech89/biome-config/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)
label._ 😀

### 🐛 Bugs

Please file an issue for bugs, missing documentation, or unexpected behavior.
  
[**See Bugs**](https://github.com/basantech89/biome-config/issues)

### 💡 Feature Requests

Please file an issue to suggest new features. Vote on feature requests by adding
a 👍. This helps maintainers prioritize what to work on.

## LICENSE

Apache 2


## NX Biome Plugin

This library was generated with [Nx](https://nx.dev).

## Building

Run `nx build biome` to build the library.

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/basantech89"><img src="https://avatars.githubusercontent.com/u/30287271?v=4?s=100" width="100px;" alt="Basant Soni"/><br /><sub><b>Basant Soni</b></sub></a><br /><a href="https://github.com/basantech89/@awesome-tools/biome/issues?q=author%3Abasantech89" title="Bug reports">🐛</a> <a href="https://github.com/basantech89/@awesome-tools/biome/commits?author=basantech89" title="Code">💻</a> <a href="https://github.com/basantech89/@awesome-tools/biome/commits?author=basantech89" title="Documentation">📖</a> <a href="#infra-basantech89" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#maintenance-basantech89" title="Maintenance">🚧</a> <a href="#plugin-basantech89" title="Plugin/utility libraries">🔌</a> <a href="#tool-basantech89" title="Tools">🔧</a> <a href="https://github.com/basantech89/@awesome-tools/biome/commits?author=basantech89" title="Tests">⚠️</a></td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td align="center" size="13px" colspan="7">
        <img src="https://raw.githubusercontent.com/all-contributors/all-contributors-cli/1b8533af435da9854653492b1327a23a4dbd0a10/assets/logo-small.svg">
          <a href="https://all-contributors.js.org/docs/en/bot/usage">Add your contributions</a>
        </img>
      </td>
    </tr>
  </tfoot>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!