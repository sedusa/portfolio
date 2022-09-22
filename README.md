# How to deploy a React App to Github Pages

![React Hero image](/src/images/react-header-image.jpg 'React Hero image')

## Introduction
In this short tutorial I'll show you how to go about creating a React application and deploying it to [Github Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages 'Github Pages') (a free web hosting service provided by Github). I will be using [create-react-app](https://create-react-app.dev 'Create React App') (a tool used to build React applications from scratch) and [gh-pages](https://www.npmjs.com/package/gh-pages 'gh-pages') (an npm package that makes deployment to Github Pages pure bliss).  
<br/>
## Tutorial
### Prerequisites
1. You need to have [Node.js](https://nodejs.org/en/ 'Node.js') and [npm](https://docs.npmjs.com/about-npm 'npm') installed on your computer. These are the versions I will be using for this tutorial (you don't have to have the same versions btw). Personally I use [nvm](https://github.com/nvm-sh/nvm 'nvm') (a version manager for node.js that allows you to quickly install and use different version of node via the command line).
```
  $ node --version
  v16.11.1

  $ npm --version
  8.0.0
```

2. You should also have `Git` installed.  The version I will be using is:
```
  $ git --version
  git version 2.37.0 (Apple Git-136)
```

3. You should have a Github account or [set one up](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account 'Setting up a Github acccount').
<br/>
<br/>
### Steps to take
### 1. Create an empty Github repository
