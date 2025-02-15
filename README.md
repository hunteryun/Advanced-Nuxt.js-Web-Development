# Advanced Nuxt.js Web Development

> Build server-side rendering (SSR) and static-generated (SSG) Vue.js applications using Nuxt.js and Composition API

This is the code repository for *Advanced Nuxt.js Web Development*, coming soon in 2023, authored by [Lau Tiam Kok](https://lauthiamkok.net/). For the time being, if you are interested in this course and have questions, please visit [lauthiamkok.net](https://lauthiamkok.net) to contact me. Otherwise, feel free to sponsor this repository to keep it going and maintained through the following channels:

* [Open Collective](https://opencollective.com/lautiamkok)
* [Ko-fi](https://ko-fi.com/lautiamkok)

## Course Overview

This repository is the successor of [*Hands-on Nuxt.js Web Development*](https://github.com/PacktPublishing/Hands-on-Nuxt.js-Web-Development). You can purchase the book of *Hands-on Nuxt.js Web Development* from [packtpub.com](https://www.packtpub.com/product/hands-on-nuxtjs-web-development/9781789952698). If you have owned the book already, which is based on Nuxt.js 2, and would like to upgrade to Nuxt.js 3 and update the old NPM packages, frameworks, and tools, please use this repository to do so. However, bear in mind that the following dependencies and skills that are covered in *Hands-on Nuxt.js Web Development* are not included in this repository and course:

* Webpack
* Backpack
* Vue CLI
* Vuex
* jQuery
* Zurb Foundation
* Swiper
* AOS
* Koa
* Express
* Keystone
* Axios
* VeeValidate (Vue form validation)
* Google OAuth/ Google APIs Node.js Client
* Prettier 
* ESLint
* jsdom
* AVA
* Nightwatch
* [Nuxt modules](https://nuxt.com/docs/guide/going-further/modules)
* [Testing](https://nuxt.com/docs/getting-started/testing)

Testing in Nuxt.js 3 is still in development. The APIs and behaviors for testing your Nuxt.js applications may change in the near future. So testing will not be included in this course. For more info about testing in Nuxt.js 3, please check it out at [https://nuxt.com/docs/getting-started/testing](https://nuxt.com/docs/getting-started/testing). However, the following NPM packages, frameworks, and tools are included and used tightly in this course (items marked with * are not covered in *Hands-on Nuxt.js Web Development*):

* Vite*
* Windi CSS*
* Less CSS
* Pinia*
* [Node.js HTTP API*](https://nodejs.org/api/http.html)
* [Node.js Fetch API*](https://undici.nodejs.org/#/docs/api/Fetch)
* Gridsome*
* Nuxt Content*
* MongoDB
* RethinkDB
* MySQL
* Socket.IO
* WordPress REST API
* Apollo Server

Whether you are coming from its predecessor or not, you still can pick up and make use of *Advanced Nuxt.js Web Development* independently. Just like its predecessor, this course is more about using Nuxt.js to connect and communicate with other Node.js and PHP applications remotely, such as Node.js HTTP applications, WordPress, and Apollo (GraphQL server). With this approach, you can keep your Nuxt.js applications as "thin" as possible while leveraging modern server-side technologies and applications. *Advanced Nuxt.js Web Development* is more focused on this idea than its predecessor. Hence, purely Vue.js-related skills are not covered in this course, such as:

* Passing down data to child components with `defineProps`
* Emitting data up to parent components with `defineEmits`
* Lazy-loading components with `defineAsyncComponent` and lazy-loading images
* Creating custom form inputs with `v-model` support
* Validating form inputs
* Creating Vue.js SSR applications using Vite SSR

If you are also interested in the preceding Vue.js essential knowledge and skills, please consider [*Advanced Vue.js Web Development*](https://github.com/lautiamkok/Advanced-Vue.js-Web-Development) too in your learning journey. You can check out [this page](https://lauthiamkok.net/origins/digital/advanced-vuejs-web-development) for how to purchase the course guide. Most importantly, *Advanced Nuxt.js Web Development* is a concise version of its predecessor. Hence, the basic and entry-level knowledge and skills are not included in this course, such as:

* What is a Vue component?
* Creating custom Vue transitions
* Writing basic MongoDB queries
* Writing MongoDB CRUD operations
* What is middleware?
* Understanding Vue transitions
* Understanding `v-model`
* Understanding session-based authentication
* What are sessions and cookies?
* The session authentication flow
* Understanding token-based authentication
* What are JSON Web Tokens?
* The token authentication flow
* Understanding HTTP messages 
* Introducing PHP and PSRs (PHP Standards Recommendations)
* Understanding the GraphQL schema and resolvers
* Understanding GraphQL default resolvers
* Understanding classic SPAs and Nuxt SPAs
* Developing a SPA with Nuxt
* Deploying a SPA and deploying to GitHub Pages
* Creating backend and frontend authentications
* Installing and securing MySQL, MongoDB, and RethinkDB
* Installing and configuring Apache, PHP, and WordPress

If you are also interested in the preceding general knowledge and skills for your Nuxt.js applications, please consider [*Hands-on Nuxt.js Web Development*](https://www.packtpub.com/product/hands-on-nuxtjs-web-development/9781789952698) too in your learning journey. *Advanced Nuxt.js Web Development* assumes you have the preceding basic knowledge and skills already. Composition API and `<script setup>` are used solely throughout the course. In other words, [Options API](https://vuejs.org/api/#options-api) and `<script>` are considered basic in this course so they are opted out entirely from the course.

## Takeaway Skills

* Create SSR and SSG Vue.js applications using Nuxt.js and Composition API

* Create dynamic pages and layouts

* Create composables, plugins, utils, and middleware

* Create responsive layouts with Windi CSS and Less

* Handle static and dynamic assets using composables

* Create a data-persistent (client-server) shopping cart system with Pinia, cookies, and composables

* Manage document head tags for SEO and Open Graph

* Create REST APIs with Node.js HTTP API, MongoDB, and MySQL for Nuxt.js applications

* Create real-time Nuxt.js applications with Socket.IO and RethinkDB

* Create a headless CMS using WordPress for Nuxt.js applications

* Connect WordPress and generate static pages with Nuxt.js

* Stream and download remote images from WordPress for static-generated sites in Nuxt.js projects

* Create HMR web servers and GraphQL servers using Vite and Node.js HTTP API for Nuxt.js applications

* Create HMR GraphQL servers with Apollo and WordPress REST API for Nuxt.js applications

* Create GraphQL APIs with Gridsome and Markdown documents for Nuxt.js applications

* Fetch data using GraphQL queries in Nuxt.js applications

* Handle HTTP errors (e.g. 404 and 500 errors) in Nuxt.js applications, Node.js applications, and PHP applications.

## Chapters and Lessons

* Chapter 1. Introducing Advanced Nuxt Web Development

    Get to know the abstract of this course, who it is for, and what it will cover, as well as the course requirements and where to download the example code files. Start a Nuxt project with Nuxi (Nuxt scaffolding tool). Explore Nuxt's project structure such as the `/pages/` and `/assets/` directories. Learn to customize your Nuxt app with the `nuxt.config` and `.env` files.

    * Knowing the Course
    * Knowing Nuxt and Starting Nuxt projects
    * Exploring the Nuxt Project Directory Structure 
    * Making Custom Configurations in Nuxt Projects

* Chapter 2. Managing Assets and Adding UI Frameworks

    Serve public and static assets such as images and fonts in Nuxt projects. Use Windi CSS as a UI framework for Nuxt apps and create responsive layouts with Windi CSS. Write CSS using Less as the CSS preprocessor in your Vue apps. Serve dynamic assets from using composables in the `<template>` block.

    * Adding UI Frameworks: Windi CSS
    * Adding CSS Preprocessors: Less
    * Serving Static Assets
    * Serving Dynamic Assets

* Chapter 3. Creating Pages, Layouts, Composables, Plugins, Utilities, and Middleware

    Create static and dynamic pages and static and dynamic routes in Nuxt apps. Create static and dynamic pages layouts with the `definePageMeta` and `setPageLayout` Nuxt APIs and the `NuxtLayout` Nuxt component. Create auto-import composables (top-level and nested) and utilities. Create client-only and server-only plugins. Install plugins using the `nuxt.config` file. Create auto-import plugins withh the `provide` plugin helper. Create global to be execute automatically when route changes manually applied. Create named middleware to be applied manually on specific pages.

    * Creating Static and Dynamic Routes
    * Creating Static and Dynamic Layouts
    * Creating Composables and Utilities
    * Creating Plugins and Middleware

* Chapter 4. Fetching Data and Handling Errors

    Fetch data from remote APIs using the the `useFetch` Nuxt API. Handle HTTP errors (e.g. 404 and 500 errors) with the `showError` Nuxt API and the `error.vue` file for unknown routes, internal server errors, and JavaScript default errors during development and runtime.

    * Fetching Data with `useFetch`
    * Creating and Handling HTTP Errors
    * Customizing the Error Page for HTTP Errors

* Chapter 5. Managing States and Stores

    Create global states with the `useState` Nuxt API to be shared between the server and client across components and pages. Manipulate global states from specific pages. Build a counter and a shopping cart system with Pinia. Create a client-server data-persistent store with the `useCookie` Nuxt API. Create a client-server data-persistent store with `localStorage` and composables.

    * Creating States with `useState`
    * Creating Stores with Pinia: Counters and Shopping Carts
    * Creating Data-Persistent Stores with Cookies
    * Creating Data-Persistent Stores with Composables

* Chapter 6. Managing Database with Nitro Server Engine in Nuxt

    Create Nuxt's built-in API layers, API routes, and API calls with server middleware, server plugins, and server utilities. Store and manage data with Nitro's default in-memory data storage. Integrate MongoDB database internally in the Nuxt apps. Use Nuxt Content module and Markdown documents as your database in the Nuxt apps.

    * Creating Server Routes, Server Middleware, Server Plugins, and Server Utilities
    * Managing Data with In-Memory Data Storage
    * Managing Data with MongoDB Database
    * Managing Data with the Nuxt Content Module

* Chapter 7. Managing Database with Node.js Apps for Nuxt

    Create Hot Module Replacement (HMR) Node.js apps with Vite, Node.js HTTP API, and `find-my-way` HTTP router. Create an HMR Node.js app with MySQL database and MongoDB database. Enable CORS in HMR Node.js apps for integrating with your Nuxt app. Create a real-time Nuxt app with RethinkDB and manage your app data with the RethinkDB database, Socket.IO, and the HMR Node.js app.

    * Creating HMR Node.js Apps with Vite and Node.js HTTP API
    * Managing Data with MySQL Database
    * Managing Data with MongoDB Database
    * Managing Real-time Data with RethinkDB Database

* Chapter 8. Managing Database with PHP Apps for Nuxt

    Create a custom REST API with WordPress and Carbon Fields (WordPress custom fields library) to serve data for your Nuxt app. Create custom fields with Carbon Fields for managing the SEO and Open Graph meta information dynamically for your Nuxt app. Create a framework agnostic PHP app that complies with PHP Standards Recommendations (PSR) to serve data for your Nuxt app.

    * Managing Data with WordPress REST APIs
    * Managing Data with PHP PSR Apps
    * Managing SEO Meta and Open Graph Meta Dynamically with WordPress

* Chapter 9. Building GraphQL Layers with MongoDB, WordPress, Gridsome and Markdown Documents for Nuxt

    Create HMR GraphQL apps with Apollo Server, Node.js HTTP API, MongoDB, an WordPress for your Nuxt app. Use Gridsome and Markdown documents as the GraphQL server and database for your Nuxt app. Fetch data from GraphQL servers using GraphQL queries in your Nuxt apps. 

    * Creating GraphQL Servers with MongoDB Database and Node.js HTTP API
    * Creating GraphQL Servers with WordPress REST APIs and Node.js HTTP API
    * Creating GraphQL Servers with Gridsome and Markdown Documents

* Chapter 10. Creating SSG Sites with Nuxt and WordPress and Going Further

    Create static-generated (SSG) sites with Nuxt and WordPress. Fetch data and stream assets from WordPress into your Nuxt project for making SSG sites. Take your Nuxt app further with testing, deployment, and other Nuxt modules and APIs. Look into options, such as using Quasar, Gridsome, and Vite SSR alone or Vite SSR plugins, for building Vue SSR and SSG apps.

    * Fetching Data from WordPress for Static Sites
    * Streaming Assets from WordPress for Static Sites
    * Going Further and Knowing Your Options
