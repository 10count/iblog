# iblog

# Vue.js Blogging Website

This is a simple blogging website built with Vue.js and Node.js. Users can create new blog posts, view a list of blogs and open blog's detailed information, and search for blogs by title. The application uses Vue Router for navigation and Vuex for state management.

## Project Setup

### Installing Dependencies
Before running the project, make sure to install the required dependencies. Use the following commands:

### Install Bootstrap library
npm install bootstrap@5

### Install Vue-router ver.4 for dividing pages
npm install vue-router@4

### Install Vuex for state management
npm install vuex@next --save

### Running the App
npm run serve

The website will be accessible at http://localhost:8080/ by default.

## Features
- Home Page: A landing page with a call-to-action to create a new blog post.
- Navigation: Bootstrap-based navbar for easy navigation to different sections of the app.
- Search: Ability to search for blogs by title.
- Detailed View: Ability to view each blog's detailed information and navigate to next/previous blog.
- Blog Creation: Users can create new blog posts, inclusing blog title, author name, blog content and main image.

## Project Structure
- src/App.vue: Main component containing the app's structure.
- src/blog.js: Mock data for blog posts.
- src/store.js: Vuex store for state management.
- src/components/...: Child components for rendering different website interface when route to the other page.
- src/assets/...: Logo and images for blog posts.

## Built With
- Vue.js
- Vue Router
- Vuex
- Bootstrap

## Author
Kim Anna
