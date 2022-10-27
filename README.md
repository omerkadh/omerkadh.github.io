# Hosting a Resume on GitHub Pages

## Purpose

In this README you will learn how to host and format an online resume using: Markdown, a text editor of your choice, GitHub, GitHub Pages, and (minimally) Jekyll. You will learn how this process relates to general principles of modern technical writing from Andrew Etter's book Modern Technical Writing.

## Contents

- [Hosting a Resume on GitHub Pages](#hosting-a-resume-on-github-pages)
  - [Purpose](#purpose)
  - [Contents](#contents)
  - [Prerequisites](#prerequisites)
  - [Instructions](#instructions)
    - [Introduction](#introduction)
    - [Hosting your resume](#hosting-your-resume)
      - [Step 1. Creating a Repository](#step-1-creating-a-repository)
      - [Step 2. Cloning a Repository](#step-2-cloning-a-repository)
      - [Step 3. Adding a Resume to a Repository](#step-3-adding-a-resume-to-a-repository)
      - [Step 4. Launching the Website](#step-4-launching-the-website)
  - [Customization](#customization)
  - [More Resources](#more-resources)
  - [Authors and Acknowledgments](#authors-and-acknowledgments)
  - [FAQ](#faq)

## Prerequisites

You will need a resume formatted in Markdown to follow these instructions. Take a look at [this](https://www.markdownguide.org/cheat-sheet) cheat sheet for a list of basic Markdown syntax; navigate [here](https://www.markdowntutorial.com/) for an interactive tutorial. Additionally, you will need:

- An internet connection
- A GitHub account

## Instructions

The following instructions are based on the GitHub Pages [quick start](https://docs.github.com/en/pages/quickstart) guide.

### Introduction

GitHub and Markdown are two of the most popular tools in today's tech industry. 

GitHub is a hosting service for Git, which is a distributed version control system (DVCS). GitHub allows users to store and share their software projects online in an environnement that will maintain and keep track of all changes made to a project.

Markdown is a lightweight markup language. In essence, markup languages text based tools which provide a syntax for users to _mark up_ text with annotations. This syntax can then be read by software to display the text in a more readable and pleasant way.

### Hosting your resume

#### Step 1. Creating a Repository

Creating a repository will take place on the GitHub landing page, _after_ you have logged in.

1. Press the green **New** button.
2. Make the **Repository name**, `username.github.io`
    - Ensure `username` is your GitHub username.
3. Ensure **Public** is checked
4. Click the green **Create repository** button.

#### Step 2. Cloning a Repository

#### Step 3. Adding a Resume to a Repository

#### Step 4. Launching the Website

## Customization

Customizing your GitHub Pages site can be simple or become incredibly complex. The reason being is that GitHub Pages uses Jekyll, a tool used to create static websites. How your site looks can be changed by using Jekyll, but alas, that won't be covered here. If you want to know more, check out the Jekyll tutorial in [More Resources](#more-resources).

## More Resources

- [Andrew Etter's _Modern Technical Writing: An Introduction to Software Documentation_](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Markdown tutorial](https://www.markdowntutorial.com/)
- [Jekyll tutorial](https://jekyllrb.com/tutorials/video-walkthroughs/)

## Authors and Acknowledgments

*This project uses the [Cayman Jekyll theme](https://github.com/pages-themes/cayman).

*Discussions in the README are based on the book, _Modern Technical Writing_ by Andrew Etter.

## FAQ

_Why is Markdown better than a word processor?_

- Markdown is better than word processors at making fast and legible documents. Markdown files are flexible that can be easily converted to other widely used file types including: XML, HTML, and JSON. Moreover, these file types can be easily rendered by websites without the required overhead when using DOCX or PDF file types.

_Why is my resume not showing up?_

- It can be a few things:
  - The filename of your resume must be either `index.md` or `README.md`. GitHub Pages prioritizes displaying `index.md`. If you want a README, your resume should be named `index.md`.
  - Ensure the GitHub Pages site is being built from the correct source branch on GitHub. This option can be found in the **GitHub Pages** section of your repository settings.
