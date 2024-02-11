# NextJS Learning Pack

This is a learning pack for NextJS. It contains a collection of resources to help you learn NextJS.

## Table of Contents

- [NextJS Learning Pack](#nextjs-learning-pack)
  - [What is NextJS?](#what-is-nextjs)
  - [Why NextJS?](#why-nextjs)
  - [Getting Started](#getting-started)
  - [Resources](#resources)
    - [Official Documentation](#official-documentation)
    - [Tutorials](#tutorials)
    - [Community](#community)
  - [Contributing](#contributing)
  - [License](#license)

## What is NextJS?
NextJS is a open source web framework built by Vercel on the React library. It is used to build production ready web applications. It is a hybrid between a static site generator and a server side rendered application.

NestJS suports styling with CSS as well as precomplied SCSS, SASS and styled JSX. It also supports TypeScript out of the box and has a file-system based routing system. 

NextJS is is used by companies like Netflix, Uber, TikTok, and many more.

## Why NextJS?

- **SEO Friendly**: NextJS is SEO friendly out of the box. It supports server side rendering and static site generation which makes it easy for search engines to crawl your website.

- **Performance**: NextJS is optimized for performance. It supports server side rendering and static site generation which makes it easy to build fast websites.

- **Developer Experience**: NextJS has a great developer experience. It supports hot module replacement, file-system based routing, and many more.

- **Hybrid**: NextJS is a hybrid between a static site generator and a server side rendered application. It supports both static site generation and server side rendering.

- **Built-in Optimizations**: NextJS has built-in automatic image, font and script optimizations.



## Getting Started

If you are experienced with React, you can get started with NextJS by following the [official documentation](https://nextjs.org/docs/getting-started).

If you are new to React, you can start by learning React first. You can learn React by following the [official documentation](https://reactjs.org/docs/getting-started.html).

You can create a new NextJS project by running the following command:

```bash
npx create-next-app@latest

# or

yarn create next-app
```

You will be asked the following questions: 
```bash
What is your project named? my-app
Would you like to use TypeScript? No / Yes
Would you like to use ESLint? No / Yes
Would you like to use Tailwind CSS? No / Yes
Would you like to use `src/` directory? No / Yes
Would you like to use App Router? (recommended) No / Yes
Would you like to customize the default import alias (@/*)? No / Yes
What import alias would you like configured? @/*
```

## This is how your project structure will look like:
![alt text](/imageAssets/image.png)   

### Now we will be explaining the NextJS project file by file: -

- **.gitignore**:    
This file is used to ignore the files and directories that you don't want to push to your git repository.

- **next-env.d.ts**:   
This file is used to declare types for NextJS.

- **package.json**:
This file is used to declare the dependencies and scripts for your project. This will have all the packages that we have installed for the specific project and the scripts that we can run for the project.

- **package-lock.json**:
This file is used to lock the versions of the packages that you have installed in your project. This is used to ensure that the same version of the package is installed in all the environments.

- **README.md**:
We use this file to describe the project and the instructions to run the project. This allows us to give a brief description of the website for developers who are new to the project.

- **tsconfig.json**:
This file is used to configure TypeScript for your project. You can configure the compiler options, include and exclude files, and many more.

- **public**:
This directory is used to store the public files like images, fonts, and many more. We use this directory to store the files that we want to be publicly accessible.

- **.eslintrc.json**:
This file is used to configure ESLint for your project. You can configure the rules, plugins, and many more. ESLint is used to find and fix problems in your JavaScript code.

- **postcss.config.js**:
This file is used to configure PostCSS for your project. You can configure the plugins, and many more. PostCSS is a tool for transforming CSS with JavaScript.

- **tailwind.config.js**:
This file is used to configure Tailwind CSS for your project. You can configure the plugins, and many more. Tailwind CSS is a utility-first CSS framework. Tailwind CSS is a in-line CSS utility to configure the CSS for the component in place. 

- **node_modules**:
This directory is used to store the installed packages for your project. This directory is created when you run the `npm install` or `yarn install` command.

- **app**:
   - **favicon.ico**:
    This file is used to set the favicon for your website. The favicon is the icon that is displayed in the browser tab.

    - **globals.css**:
    This file is used to set the global styles for your website. You can set the global styles like the font-family, font-size, and many more.

    - **layout.tsx**:
    This file is used to set the layout for your website. You can set the layout for your website like the header, footer, and many more. We can arrange the elements in the page using the layout.tsx file. Each page will have a layout.tsx file which will be used to set the layout for the page. These are a set of components that are used to set the layout for the website.

    - **page.tsx**:
    This file is used to set the page for your website. You can set the page for your website like the home page, about page, and many more. We can arrange the elements in the page using the page.tsx file. Each page will have a page.tsx file which will be used to set the information for the page. These are a set of components that are used to design the screen for the website. 
    

## Deep Dive: 
We will be adding detailed comments to the pages and layout files to explain the code in detail.

