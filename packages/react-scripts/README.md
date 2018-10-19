# Create React App - Better SASS Support   
> :warning: This is a fork of [Create React App 2] (CRA2) (https://github.com/facebook/create-react-app) specifically to address the issue when opting in to [using node-sass](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-a-sass-stylesheet). Where the node_modules is not in the included path, causing third party component libraries such as [React MDC](https://github.com/material-components/material-components-web-react) to be tricky to implement with out ejecting your CRA project. 

## Installation
This fork is intended to be used in conjunction with CRA2, if you are using SASS in your project.

**Step 1: install node-sass** 
Please you have followed the steps as stated [Adding a Sass Stylesheet](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-a-sass-stylesheet) Section. 

**Step 2: Remove React-Scripts**

    npm uninstall react-scripts

> This step is important!
>
**Step 3: Install improved react-scripts**

    npm install -save @tdkrage-oss/react-scripts
**DONE!**

Your app can now do sass imports from node_modules with out he use of a ~. 

# react-scripts

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://github.com/facebook/create-react-app/blob/master/README.md#getting-started) – How to create a new app.
- [User Guide](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md) – How to develop apps bootstrapped with Create React App.
