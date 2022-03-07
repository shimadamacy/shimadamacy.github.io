---
title: Start github pages with gatsby
date: "2022-03-05T22:40:32.169Z"
description: This is a custom description for SEO and Open Graph purposes, rather than the default generated excerpt. Simply add a description field to the frontmatter.
---

git noreply email
https://qiita.com/sta/items/982ab68e8220a81d485c

reference)
https://daveceddia.com/start-blog-gatsby-netlify/

npm install -g gatsby-cli
gatsby new my-blog https://github.com/gatsbyjs/gatsby-starter-blog
cd my-blog
git branch -M main
git remote add origin <your-git-repository>
git push -u origin main

npm install -g yarn
yarn add gh-pages

add here's command into package.json script 

"deploy": "gatsby build && gh-pages -d public"