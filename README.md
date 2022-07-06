# svelteApp
Handling Pagination in Strapi v4 with SvelteKit

# reference

site: https://medium.com/strapi/how-to-handle-pagination-in-strapi-v4-with-sveltekit-d3dd8191137b  

# strapi

Strapi is a headless CMS (content management system) for Node.js to build and develop APIs.  

# svelteKit

To build the frontend, you’ll use SvelteKit, which is a framework for building web applications of all sizes. It gives you the best frontend and backend capabilities in a single-page application.  

# history
```sh
mkdir strapi-svelte-pagination

# Strapi v4 Setup
npx create-strapi-app@latest backend --quickstart
# Installing NPM packages 
npm install --save-dev @faker-js/faker
# Creating faker/seed data.
cd backend
mkdir backend/src/utils/
touch backend/src/utils/seed.js
vi backend/src/utils/seed.js
# run strapi.
npm run develop

# Creating the Article Collection Type
# Seeding Strapi with Articles
# Setting Up Permissions for Strapi Article API

# svelte setup
npm init svelte@next frontend
# Installing NPM Packages
cd frontend
npm install axios qs
# Feching Articles from Strapi
vi frontend/src/routes/index.svelte
# run svelete
npm run dev
# implementing Pagenation Controls in Svelte
vi frontend/src/routes/index.svelte
```

# package version

node : v16.15.1  
npm : 8.11.0  

## frontend
sveltejs : ^3.44.0  

## backend
strapi : 4.2.2  


