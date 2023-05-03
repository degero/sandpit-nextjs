# Nextjs TS app

## About
From tutorial
https://nextjs.org/learn/basics/create-nextjs-app

Uses SSG data, file routing and links, dynamic routes, header changes for title, image optimisation

Uses grey matter lib for injecting data to /posts/*.md files
npm install gray-matter

Uses remark to render .md blog post files
npm install remark remark-html

Uses date-fns for date string render
npm install date-fns

Uses sharp for image optimisation
npm install sharp
## Setup
install npm 12+
npm i
npm run dev

## Production
Set env vars for undefined ones in .env.production / build run with env NODE_ENV set to production