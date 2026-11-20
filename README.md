# Article Library

[![License: Apache-2.0](https://img.shields.io/github/license/rajumuke-dev/article_library)](LICENSE) [![Rails](https://img.shields.io/badge/Rails-6.0-red)](#) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md) [![Stars](https://img.shields.io/github/stars/rajumuke-dev/article_library?style=social)](https://github.com/rajumuke-dev/article_library)

A small Ruby on Rails app built while learning the framework: create, read, update and delete articles (title and description).

## Features
- Full CRUD for articles (`/articles`)
- Home page at `/`
- SQLite database, zero setup

## Requirements
- Ruby 2.6.3
- Node.js and Yarn
- SQLite3

## Run locally
```
bundle install
yarn install
bin/rails db:setup
bin/rails server
```
Open http://localhost:3000.

## Tests
```
bin/rails test
```

## Contributing and security
Fork, branch, and open a Pull Request; see [CONTRIBUTING.md](CONTRIBUTING.md). Report vulnerabilities privately per [SECURITY.md](SECURITY.md). Licensed under [Apache-2.0](LICENSE).
