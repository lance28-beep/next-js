## Next Js Tutorial:
[code_evolution](https://www.youtube.com/watch?v=9P8mASSREYM&list=PLC3y8-rFHvwgC9mj0qv972IO5DmD-H0ZH)

## Introduction

<code>What is Next.js?</code>
- <b>The react framework for production</b><br>
- React
    -  Not quite possible to build a full feature rich application ready to be deployed for production
    - React is a library for building user interfaces.
    - You have to make decision on other features of the app like routing, styling, authentication etc.
- Next.js
    - a package that uses Reac for building user interfaces.
    - Loaded with a lot more features that enable you to build full fledged production ready applications.
    - Features exactly like routing, styling, authentication, bundle optimization etc.
    - Theres no need to install additional packages.Next.js provides everything for you.
    - Opinions and conventions need to be followed to implement the above said features

<code>Why Learn Next.js</code><br>
- Next.js simplifies the process of building a react application for production. 
    - File Based Routing
    - Pre-rendering
    - API Routes
    - Support for CSS modules
    - Authentication
    - Dev and Prod Build system<br>

<code>Why Learn Next.js</code><br>
- HTML,CSS and Javascript Fundamentals
- ES6 + features
- React Fundamentals

<hr>

## Hello World

<code>create a project</code><br>
```
npx create-next-app name-of-file
```

<code>run the project</code><br>

```
npm run dev
```
```
> hello-world@0.1.0 dev /home/rolando/Desktop/learn-new-stacks/hello-world
> next dev

ready - started server on 0.0.0.0:3000, url: http://localhost:3000
info  - Using webpack 5. Reason: Enabled by default https://nextjs.org/docs/messages/webpack5
```
<img src='./img/welcome.png' width='500'><br>

<hr>

## Project Structure

<code>package.json</code>
- this file contains the dependencies and the scripts required for the project<br>
```
{
  "name": "hello-world",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },
  "dependencies": {
    "next": "11.0.1",
    "react": "17.0.2",
    "react-dom": "17.0.2"
  },
  "devDependencies": {
    "eslint": "7.32.0",
    "eslint-config-next": "11.0.1"
  }
}

```

<code>"dependencies"</code>

<code>"devDependencies"</code>