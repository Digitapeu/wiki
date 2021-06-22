# E2E tests

*The Front-end repo can be found [here](https://bitbucket.org/digitapeu/nuxt.wam.app/src/master/).*

## Setup

1. Make sure to have the right environment variables:

```bash
cp .env.example .env
```

2. Quickly access the Nightwatch API

```bash
# This will open up the TypeScript Declaration File for Nightwatch.
code -r node_modules/@types/nightwatch/index.d.ts
```

---

## Run the E2E tests locally

```bash
env $(cat .env) npm run e2e
```

### Run a specific E2E test

```bash
env $(cat .env) npm run e2e -- --test path/to/test/file
```

---

## Create a new test

You can add a new file for each flow that you want to test(e.g *user log in*, *payment flow*). 

In order to benefit from autocompletion and generally a better developer experience while writing such tests, you'll have to have this at the beginning of the file:

```js
/**
 * @typedef { import("@types/nightwatch/index").NightwatchAPI } NightwatchAPI
*/
```

and when writing test cases, you should have this structure:

```js
{
  /**
    * @param {NightwatchAPI} browser
  */
  'Log in with Email & Password': browser => { }
}
```