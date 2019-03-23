# Own Courses Server OpenAPI Specification

[![Build Status](https://travis-ci.com/owncourses/server-api-spec.svg?branch=master)](https://travis-ci.com/owncourses/server-api-spec)

## Links

- [Reference Documentation (ReDoc)](https://owncourses.github.io/server-api-spec/)
- [SwaggerUI](https://owncourses.github.io/server-api-spec/swagger-ui/)
- OpenAPI Raw Files: [JSON](https://owncourses.github.io/server-api-spec/openapi.json) [YAML](https://owncourses.github.io/server-api-spec/openapi.yaml)

**Warning:** All above links are updated only after Travis CI finishes deployment

## Working on specification

### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`

Starts the development server.

#### `npm run build`

Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`

Validates the spec.

#### `npm run gh-pages`

Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
