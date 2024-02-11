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

## Learn HTML Code 


### 1. Understanding HTML:

- **HTML Definition**: HTML stands for Hypertext Markup Language. It is the standard markup language for creating web pages and web applications.
- **How HTML Works**: HTML documents are text files containing HTML elements enclosed in tags. Browsers render HTML documents based on these tags.

### 2. Setting Up:

- **Text Editor**:
  - Download and install a text editor like Visual Studio Code (VS Code).
- **Browser**:
  - Install a modern web browser like Google Chrome or Mozilla Firefox.

### 3. Learning HTML Fundamentals:

- **HTML Document Structure**:
  ```html
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Document</title>
  </head>
  <body>
      <!-- Content goes here -->
  </body>
  </html>
  ```
- **Tags and Elements**:
  ```html
  <h1>This is a Heading</h1>
  <p>This is a paragraph.</p>
  <a href="https://example.com">This is a link</a>
  <img src="image.jpg" alt="Description of the image">
  ```
- **Attributes**:
  ```html
  <img src="image.jpg" alt="Description of the image">
  <a href="https://example.com" target="_blank">Open link in a new tab</a>
  ```

### 4. Basic HTML Elements:

- **Text Formatting**:
  ```html
  <p><strong>Bold text</strong>, <em>italic text</em>, <u>underlined text</u></p>
  ```
- **Lists**:
  ```html
  <ul>
      <li>Item 1</li>
      <li>Item 2</li>
  </ul>

  <ol>
      <li>Item 1</li>
      <li>Item 2</li>
  </ol>
  ```
- **Tables**:
  ```html
  <table>
      <tr>
          <th>Name</th>
          <th>Age</th>
      </tr>
      <tr>
          <td>John</td>
          <td>30</td>
      </tr>
      <tr>
          <td>Jane</td>
          <td>25</td>
      </tr>
  </table>
  ```

### 5. Intermediate HTML:

- **HTML5 Features**:
  ```html
  <video controls>
      <source src="movie.mp4" type="video/mp4">
      Your browser does not support the video tag.
  </video>

  <audio controls>
      <source src="music.mp3" type="audio/mpeg">
      Your browser does not support the audio tag.
  </audio>
  ```

### 6. Advanced HTML:

- **HTML Metadata**:
  ```html
  <head>
      <meta charset="UTF-8">
      <meta name="description" content="Description of your webpage">
      <meta name="keywords" content="HTML, CSS, JavaScript">
      <title>My Webpage</title>
  </head>
  ```
- **Character Encoding**:
  ```html
  <meta charset="UTF-8">
  ```

### 7. HTML Validation:

- **W3C Markup Validation Service**: Visit [W3C Markup Validation Service](https://validator.w3.org/) and input your HTML code to validate it.

### 8. Practice and Projects:

- **Practice**:
  - Create simple HTML pages and experiment with different elements and attributes.
- **Mini-Projects**:
  - Build a personal portfolio website, a blog template, or a simple calculator application using HTML.

### 9. Additional Resources:

- **Books**:
  - "HTML and CSS: Design and Build Websites" by Jon Duckett
  - "Learning Web Design" by Jennifer Robbins
- **Documentation**:
  - [HTML Living Standard](https://html.spec.whatwg.org/)
  - [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

### 10. Community and Support:

- **Online Communities**:
  - Join forums like Stack Overflow, Reddit's r/webdev, GitHub, etc., for discussions and support.
- **Code Reviews**:
  - Seek feedback on your HTML code from peers or mentors to improve your skills.

## Learn CSS Code
Certainly! Let's create an extremely detailed guide with code snippets to learn CSS (Cascading Style Sheets):

### 1. Understanding CSS:

- **What is CSS?** CSS (Cascading Style Sheets) is a style sheet language used for describing the presentation of a document written in HTML or XML.
- **How does CSS work?** CSS allows you to style HTML elements by specifying rules that define how elements should be displayed.

### 2. Setting Up:

- **Integration**: CSS can be included in an HTML document internally, externally, or inline.
- **Text Editor**: Choose a text editor like Visual Studio Code, Sublime Text, or Atom for writing CSS code.
- **Browser**: Use a modern web browser (Chrome, Firefox, Safari, Edge) to view and test your CSS styles.

### 3. Learning CSS Fundamentals:

- **Selectors**: Understand CSS selectors, which are patterns used to select the elements you want to style.
- **Properties and Values**: Learn about CSS properties and their corresponding values. Properties define what aspects of the selected elements you want to style, and values specify how you want to style them.
- **Box Model**: Understand the CSS box model, which describes how elements are rendered on the web page as rectangular boxes with content, padding, borders, and margins.
- **Layout**: Explore different layout techniques such as flexbox and CSS grid for positioning and arranging elements on the web page.
- **Responsive Design**: Learn how to create responsive designs using media queries to adapt the layout and styling based on the device's screen size.

Of course! Here are some code snippets demonstrating various CSS concepts and techniques:

### 4. Basic CSS Styles:

- **Colors**:
  ```css
  /* Using hexadecimal color */
  color: #ff0000;

  /* Using RGB color */
  background-color: rgb(255, 0, 0);

  /* Using RGBA color with transparency */
  border: 1px solid rgba(0, 0, 255, 0.5);

  /* Using HSL color */
  color: hsl(0, 100%, 50%);

  /* Using HSLA color with transparency */
  background-color: hsla(120, 100%, 50%, 0.3);
  ```

- **Fonts**:
  ```css
  /* Specifying font family */
  font-family: Arial, sans-serif;

  /* Setting font size */
  font-size: 16px;

  /* Setting font weight */
  font-weight: bold;

  /* Setting font style */
  font-style: italic;
  ```

- **Text Styles**:
  ```css
  /* Changing text color */
  color: #333;

  /* Aligning text */
  text-align: center;

  /* Adding text decoration */
  text-decoration: underline;

  /* Setting line height */
  line-height: 1.5;

  /* Adjusting letter spacing */
  letter-spacing: 2px;
  ```

- **Backgrounds**:
  ```css
  /* Setting background color */
  background-color: #f0f0f0;

  /* Adding background image */
  background-image: url('background.jpg');

  /* Repeating background image */
  background-repeat: repeat-x;

  /* Setting background size */
  background-size: cover;
  ```

### 5. Intermediate CSS:

- **Transitions**:
  ```css
  /* Adding transition to a property */
  transition: background-color 0.3s ease-in-out;

  /* Hover effect with transition */
  button {
      background-color: #3498db;
      transition: background-color 0.3s ease-in-out;
  }
  button:hover {
      background-color: #2980b9;
  }
  ```

- **Transformations**:
  ```css
  /* Transforming elements */
  .box {
      transform: rotate(45deg);
  }

  /* Combining transformations */
  .box {
      transform: translate(50px, 50px) rotate(45deg) scale(1.5);
  }
  ```

- **Animations**:
  ```css
  /* Defining keyframes */
  @keyframes slide {
      0% { left: 0; }
      100% { left: 100%; }
  }

  /* Applying animation */
  .slider {
      animation: slide 2s infinite;
  }
  ```

- **Flexbox**:
  ```css
  /* Creating flex container */
  .container {
      display: flex;
      justify-content: center;
      align-items: center;
  }

  /* Flex item properties */
  .item {
      flex: 1;
  }
  ```

- **Grid**:
  ```css
  /* Creating grid container */
  .container {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-gap: 10px;
  }

  /* Grid item properties */
  .item {
      grid-column: span 2;
  }
  ```

### 6. Advanced CSS:

- **CSS Variables**:
  ```css
  /* Defining CSS variables */
  :root {
      --primary-color: #3498db;
  }

  /* Using CSS variables */
  button {
      background-color: var(--primary-color);
  }
  ```

- **Pseudo-classes and Pseudo-elements**:
  ```css
  /* Styling links on hover */
  a:hover {
      text-decoration: underline;
  }

  /* Adding content before an element */
  .icon::before {
      content: "\f005"; /* Unicode character for star */
      font-family: "Font Awesome";
  }
  ```

- **Responsive Design Best Practices**:
  ```css
  /* Media query for mobile devices */
  @media (max-width: 768px) {
      .container {
          flex-direction: column;
      }
  }

  /* Fluid typography */
  body {
      font-size: 16px;
  }
  @media (min-width: 768px) {
      body {
          font-size: 18px;
      }
  }
  ```

