# PatrykB's Create React App template

Hello!

This is my first very own CRA template. I figured I spend too much time setting up my React projects from scratch, so I decided to create this template to easily automate some typical tasks that are common in my React projects.

## Tech stack

This template includes following features:

- TypeScript
- Eslint (custom instance, not the React's default one)
- Prettier
- Husky
- lint-staged
- Storybook

This template also uses `cross-env` in order to ensure all operating systems and shells will display colorized messages with lint-staged and Husky.

At one point I also wanted it to contain Storybook, but with its CLI nowadays it's super-easy to install it manually. :) And having it pre-installed with the template caused packages conflict (mainly with babel-loader and webpack).

To install Storybook in your CRA project, simply use the following command:

```
npx sb init --type react
```

## Installation

To use this template, simply run this command in your command line tool:

```
yarn create react-app <app-name> --template cra-template-patrykb
```
