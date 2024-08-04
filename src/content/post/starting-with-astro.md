---
title: "Getting Started with Astro JS: A Complete Beginner's Guide"
description: "Explore Astro JS from scratch to advanced techniques. Build fast, modern websites with this powerful framework"
publishDate: "04 August 2024"
tags: ["astrojs", "javascript", "frontend", "webdevelopment", "beginners"]
---

## Introduction

Astro JS is a modern framework for building fast and SEO-friendly static websites. This article will guide you through the basics of Astro JS, why you should use it, and how to start your first project.

## Why Choose Astro JS?

Astro JS offers high speed and performance with an architecture that focuses on delivering only static HTML to the browser. This means your site will be faster, lighter, and easier to optimize for search engines.

## Setting Up the Development Environment

Before starting with Astro JS, make sure you have Node.js and npm installed on your computer. Follow these steps to set up your development environment:

1. Install Node.js and npm from the official [Node.js](https://nodejs.org/en) website.
2. Create a new project with the command:

```html
npm create astro@latest
```

## Creating Your First Project

Let's create our first Astro JS project. Use the following command to create a new project:

```html
npm create astro@latest
```

Choose the desired template or use the default template to get started. Once the project is created, navigate to the project directory and start the development server with:

```html
npm start
```

Open your browser and access `http://localhost:3000` to see your first Astro JS project.

## Adding Content

Astro JS allows you to create static pages easily. Create an index.astro file in the src/pages directory and add the following HTML content:

```html
---
title: "Home"
---

<!doctype html>
<html>
	<head>
		<title>Home</title>
	</head>
	<body>
		<h1>Welcome to Astro JS!</h1>
		<p>This is your first page.</p>
	</body>
</html>
```

Save the file and see the result in the browser.

## Using Components

Astro JS supports using components from various frameworks like React, Vue, and Svelte. Here is an example of using a React component in an Astro JS project:

1. Install React and React DOM with the command:

```html
npm install react react-dom
```

2. Create a `Button.jsx` file in the `src/components` directory with the following content:

```html
import React from 'react'; function Button() { return (
<div className="button">
	<button>Click me!</button>
</div>
); } export default Button;
```

3. Use the component in the `index.astro` file:

```html
---
import Button from '../components/Button.jsx';
---

<h1>Welcome to Astro JS!</h1>
<button />
```

## Finalizing and Publishing the Project

Once you are satisfied with your project, it's time to publish it. Use the following command to build the project:

```html
npm run build
```

The build output will be in the `dist` directory. You can host your site on static hosting platforms like [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/).

## Conclusion

Astro JS is an excellent choice for building fast and SEO-friendly static websites. By following this guide, you now have a solid foundation to start exploring and building your own projects with Astro JS.
