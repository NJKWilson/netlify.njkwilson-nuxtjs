---
title: Getting Started
version: 0.1
badge: 'Version 0.1'
createdAt: "2020-06-22"
updatedAt: "2020-06-22" 
description: ''
position: 1
category: 'Introduction'
techs: 
  - Vue.Js
  - Nuxt.Js
  - Tailwind
---

## Why are we here

The purpose of this site is to document the process of generating static websites that can be deployed to a webserver in plain HTML/CSS/JS using Nuxt.Js as a Static Site Generator (SSG).

I will also
- Create styled reusable components and give instructions on how to incorperate them into a project.
- Explain how to use Vue.Js Loops and Condition Statments
- Explain how to do on page SEO
- Explain Vuex Stores

## What we will use

<list :items="techs"></list>

## What is an SSG

A static site generator (SSG) is a tool that can be used to create websites without having to hand-code each individual page in HTML. 

A SSG can utilise templates so that Headers, Footers, Nav Bars, etc. can be written once and then reused on every page, you can also use raw data from sources such as markdown files or databases to create the actual content of a site page.

As an example you can create a websites template once (Headers, Footers, Nav Bars, etc) and leave a 'placeholder' so that when you generate your site the SSG will pull raw data from your datasource (Markdown/Database/Json) and generate a html page per Markdown document using your template but replacing the 'placeholder' with the content of the Markdown document.

Why is this good? Say you have 100 Blog Posts, if you hand code each page but then want to add a link to the footer you would have to manually change 100 pages with an SSG you would only have to change your template and regenerate the site.

## What is Nuxt.JS

Nuxt.js is a framework that utilises Vue.js to create web applications, it can be used to create a Server Rendered Application, Single Page Application or a Static Generated Site.

This site will be focused on using the SSG functionality of Nuxt.Js but alot of this documenation can be used on all three options.