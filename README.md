#Collection of ugly useless buttons for your displeasure
##made by yours truly

The goal of this Single Page Appliction (SPA) is to showcase buttons that
do some useless stuff for pure entertainment and nothing else, as I have
run out of ideas and inspiration.

##Link for your enjoyment:
[Click me pls](https://zesty-lily-41decc.netlify.app)
[Storybook here](https://www.chromatic.com/build?appId=63ed1e7029d46728c55748d3&number=3)

---

##Installation:

> npm install

##Running the app:

> npm run dev

---

##Tools used:

+Prettier - used to enforce a certain code style and format it on command, based
on provided rules

- Eslint

  - similarly to Prettier, linters are used to spot patterns and provide
    the same consistent style of code across the board by the entire team
    (or in this case, just me)

- Husky

  - an package that lets you create custom hooks to run against your repository
    before commiting changes, to flag any issues/errors/code inconsistencies

- Lint-staged

  - runs linter on git commit command against all staged files

- Vitest

  - a unit test framework built based on Vite, chosen by me due to simplicity
    and speed of testing

- Storybook
  - a tool for UI development, mainly used for building components and pages
    in isolation from your dev stack

---

##Scripts used:

- "dev":

  - starts a dev server

- "build":

  - build for production

- "preview":

  - locally preview the production build

- "format":

  - Prettier formats and overwrites the files if there's anything to correct

- "check":

  - Prettier checks if files are formatteed without overwriting

- "prepare":

  - install Husky and prepare hooks

- "lint":

  - lints all TypeScript and Vue code

- "test":

  - runs all unit tests

- "coverage":

  - runs tests with civerage (measurement of how many lines of code are
    executed while the tests are running)

- "storybook":

  - starts a Storybook "instance" locally at :6006

- "build-storybook":
  - builds a production Storybook version

---

##Hooks used:

+npm test: - runs tests on git commit command

---

#Github actions used:

- Test

  - runs tests against commited code on git push command

- Eslint & Prettier
  - runs eslint and prettier on git push command
