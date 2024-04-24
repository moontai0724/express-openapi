# @moontaiworks/express-openapi-typebox

[![NPM Version](https://img.shields.io/npm/v/@moontaiworks/express-openapi-typebox)](https://www.npmjs.com/package/@moontaiworks/express-openapi-typebox)
[![NPM Downloads](https://img.shields.io/npm/d18m/@moontaiworks/express-openapi-typebox)](https://www.npmjs.com/package/@moontaiworks/express-openapi-typebox)
[![Codecov](https://codecov.io/gh/moontaiworks/express-openapi-typebox/graph/badge.svg)](https://codecov.io/gh/moontaiworks/express-openapi-typebox)

Express + OpenAPI + TypeBox document generation & input validation by ajv.

## Install

### NPM

```bash
npm install @moontaiworks/express-openapi-typebox
```

### Yarn

```bash
yarn add @moontaiworks/express-openapi-typebox
```

### PNPM

```bash
pnpm add @moontaiworks/express-openapi-typebox
```

## Usage

```typescript
import { add, divide, max } from "@moontaiworks/express-openapi-typebox";

add(1, 2); // 3
divide(1, 2); // 0.5
max(1, 2); // 2
```

## API Document

See the [API documentation](https://moontaiworks.github.io/express-openapi-typebox/).
