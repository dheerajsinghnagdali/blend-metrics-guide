# A guide on formatting, linting, and Blend Metrics' libraries

## Next.js

We're using Next.js in every single font-end. When you configure a project using Next.js, you get a lot things configured that are mentioned below.

## Typescript

We're supposed to use Typescript. And we would appreciate if you could make types performant, and use advanced Typescript features such as generics, mapped types, the infer keyword, and so on where appropriate. When configuring Next.js, choose Typescript, so that you don't have to configure it manually.

## Formatting

We're using Prettier, and in order to format imports we're using [Prettier Plugin Sort Imports](https://github.com/trivago/prettier-plugin-sort-imports) by Trivago.

## Linting

We're using Eslint, and it gets configured by Next.js itself. We're using a Eslint Prettier plugin which you can configure using [this guide by Next.js](https://nextjs.org/docs/app/building-your-application/configuring/eslint#prettier).

## Conventional commits

We're using conventional commits, if you need a quick reference follow [this guide](https://www.conventionalcommits.org/en/v1.0.0/). You can do this with Commitlint, and in order to configure it locally, you can refer to [this guide](https://commitlint.js.org/#/guides-local-setup). Moreover, you in order to make Commitlint work, you will have to configure Husky. Here's a [guide](https://typicode.github.io/husky/getting-started.html). Using Husky, you can add pre-commit hooks in order to check formatting and if you have any lint errors.

## We're using our own libraries `blend-metrics/ui` and `@blend-metrics/icons`

In order to use these libraries, you just need to install them through npm. Here's a [guide](https://github.com/dheerajsinghnagdali/blend-metrics-getting-started) on how you can configure our libraries.

Here's [the design system's Storybook](https://blend-metrics-ui.vercel.app/) which you can use in order to see all the components available. We're using Radix UI, Headless UI, and Zag.js. Radix UI has been used heavily, so in order to see all the props of most of the components, refer to Radix UI's documentation. Some of them are using Headless UI, so you've got to refer to Headless UI's documentation. Those components are Combobox, and Listbox. And two components are using Zag.js which are Pin Inputs. Dropzone components are using `react-dropzone`.

### How you should name your files

Next.js has been using kebab case for its website and at Vercel. So it's become a convention. As you're using Next.js, you should also use kebab case when it comes to naming files. If you're not sure about kebab case, [this guide](https://developer.mozilla.org/en-US/docs/Glossary/Kebab_case) could potentially helpful for you.

### How you should name your variables and function

Developers like to use the convention they like. However, at Marketkeq, we like to move forward professionally. So we would appreciate if you follow [this guide](https://github.com/kettanaito/naming-cheatsheet) in order to name your variables and functions. Our whole codebase is based on functional programming. So we would appreciate if you don't use classes anywhere. And you are suppposed to use [the camel case](https://developer.mozilla.org/en-US/docs/Glossary/Camel_case) convention when it comes to naming variables and functions.
