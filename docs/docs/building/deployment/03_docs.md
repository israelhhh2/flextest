---
title: Docs
---

The `docs` package is responsible for maintaining the documentation for the project template, and is the source code for this live site.

This website is built using [Docusaurus 2](https://docusaurus.io/), in hopes of building better organized documentation around what the Flex Project Template is, how to get started and build with it, and provide a starting point for customers to document their functionality.

The live documentation site can be found [here](https://twilio-professional-services.github.io/flex-project-template/), but can also be run locally by executing the following at the root directory of the template (after running `npm i` in the `/docs` folder):

```
npm run start:docs
```

## Deploying your own docs site

When customizing the template, you may want to have your own documentation site for reference.

The Docusaurus site will be deployed to GitHub Pages by the `Docs Deploy` workflow if the repository variable `DEPLOY_DOCS` is set to `true`.