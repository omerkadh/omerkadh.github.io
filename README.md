# Hosting a Resume on GitHub Pages

## Purpose

In this README you will learn how to host and format an _online_ resume using: [Markdown](https://www.markdownguide.org/getting-started/), a [text editor](https://code.visualstudio.com/), [GitHub](https://github.com/), [GitHub Pages](https://pages.github.com/), and (minimally) [Jekyll](https://jekyllrb.com/docs/). As a beginner, You will learn a little bit about these tools and how this process relates to the important principles of modern technical writing outlined in Andrew Etter's book, "_Modern Technical Writing_".

## Contents

- [Hosting a Resume on GitHub Pages](#hosting-a-resume-on-github-pages)
  - [Purpose](#purpose)
  - [Contents](#contents)
  - [Prerequisites](#prerequisites)
  - [Instructions](#instructions)
    - [Introduction](#introduction)
    - [Step 1. Create a Repository](#step-1-create-a-repository)
    - [Step 2. Copy your Markdown formatted resume into a README.md file](#step-2-copy-your-markdown-formatted-resume-into-a-readmemd-file)
    - [Step 3. Configure the repository settings to host the resume online](#step-3-configure-the-repository-settings-to-host-the-resume-online)
    - [Step 4. Visit your website](#step-4-visit-your-website)
  - [Customization](#customization)
  - [More Resources](#more-resources)
  - [Authors and Acknowledgments](#authors-and-acknowledgments)
  - [FAQ](#faq)

## Prerequisites

You will need a resume formatted in Markdown to follow these instructions. Take a look at [this](https://www.markdownguide.org/cheat-sheet) cheat sheet for a list of basic Markdown syntax; navigate [here](https://www.markdowntutorial.com/) for an interactive tutorial. Additionally, you will need:

- An internet connection
- A GitHub account  
NOTE: Follow [this](https://github.com/) link to GitHub and click "_sign up_" in the top right corner to begin the account creation process. You will need an existing email, username, and password. Once you've finished the creation process, or if you already had an account and signed in, proceed to the [instructions](#instructions).

## Instructions

The following instructions are based on the GitHub Pages [quick start](https://docs.github.com/en/pages/quickstart) guide.

### Introduction

GitHub and Markdown are two of the most popular tools in today's tech industry.

[GitHub](https://docs.github.com/en/get-started/quickstart/hello-world) is a hosting (containing) service for [git](https://git-scm.com/), which is a [distributed version control system](https://en.wikipedia.org/wiki/Distributed_version_control) (DVCS). GitHub allows users to store and share their software projects online in an environnement that will maintain and keep track of all changes made to a digital project. GitHub can help you "Catalog the Diff" as Andrew says in his book. As you make edits on this and future products, a changelog serves as a catalog of all your progress; this can help viewers gain confidence in your project and get an idea of the overall direction you're heading.

Markdown is a lightweight markup language written in regular plain text (like a .txt file). In essence, markup languages are text based tools which provide a syntax for users to _mark up_ the text with annotations. This syntax can then be read by software to display the text in a more readable and pleasant way.  
NOTE: anytime a SomeName.md file is mentioned, we are talking about a Markdown file.

### Step 1. Create a Repository

Now that you have a GitHub account, the first thing you need to do is create a new repository to host (hold) the resume you will be hosting online. Begin from your "_personal dashboard_" which is the first page you see after logging in.  
NOTE: You can think of a repository as the top level director on a file system, with virtually any number of sub directories you like. See [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories) for more information.

1. Click the "_plus_" icon next the the "_bell_" in the top right corner of the dashboard.
2. Click "_New repository_".
3. Enter "_YourUsername.github.io_" under "_Repository name_", replacing "_YourUsername_" with the username for your GitHub account.  
NOTE: This specific naming scheme is _essential_ for the hosting to work. In brief, it tells github that this repository will be used for online hosting.
NOTE: Ensure "_Public_" is selected, not "_Private_".
4. Scroll down and click the green "_Create repository_" button.  
RESULT: You will see a sort of quick setup page. Everything here can be ignored besides the "_README_" hyperlink.
5. Click the hyperlink labeled "_README_". It is located under and to the right of the "_Quick setup_" heading, in the same rectangular section.  
NOTE: This README.md file is where you will paste your resume.
6. Scroll down to the bottom of the page.
7. Click "_Commit new file_".  
NOTE: It doesn't matter what is currently in the README.md file; you can edit the file at any time.

Another important suggestion by Andrew is to use a DVCS. While the capabilities of a system like git may exceed what is needed for software documentation, not using a DVCS is a wasted opportunity. Almost every large software company uses some kind of DVCS, so a technical writer that refuses to follow suit is not a good look. Additionally, since most of the software a writer is documenting will itself be using a DVCS, using a DVCS for documentation presents the opportunity to keep code and documentation close together. As the code progresses, so too can the documentation. And as developers continue to work on code, it may be more likely for them to contribute to the documentation themselves.

### Step 2. Copy your Markdown formatted resume into a README.md file

The README.md file will automatically be recognized by GitHub and used to populate your website. Thus, pasting your Markdown formated resume here is the simplest method for hosting your resume online.  
To start, you should be viewing the "_Code_" tab within your repository. If you are just returning to the GitHub [website](https://github.com/), you should be at your dashboard. Click on the icon to the right of the "_plus_" sign on the top right of the page, then click "_Your repositories_". Select the YourUsername.github.io repository you created earlier.

1. Click on "_README.md_".
   - You should see a preview of the "_README.md_" file which may contain 0 lines (1 blank line on the preview).
2. Click the pencil icon above the preview to edit the file.
3. Paste or type your Markdown formatted readme file in the text box.
4. Scroll to the bottom of the page.
5. Click "_Commit changes_".

As Andrew says in his book, lightweight markup languages such as Markdown are essential for a technical writer. Compared to a document in [XML](https://www.w3.org/standards/xml/core#:~:text=What%20is%20XML%3F,more%20suitable%20for%20Web%20use.), which is not a _lightweight_ markup language, the same document in Markdown would likely have half the amount of text, be much easier to read, be much easier to write. Furthermore, Markdown syntax is quicker and easier to learn. When sharing documentation in a public repository such as this one, the accessability this affords is important to allow shared contributions. Other options such as specialized editors for XML and Microsoft Word are both expensive and, in the case of Word, require specific software to view. On the other hand, free text editors are available on almost any computer and provide all you need to view and edit Markdown files.

### Step 3. Configure the repository settings to host the resume online

Like in [Step 2](#step-2-copy-your-markdown-formatted-resume-into-a-readmemd-file), you will first need to be in your _YourUsername.github.io_ repository. Here we will configure the source of data for your website, the particular [branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches) to pull from, and the folder within that branch to pull from.

1. Click the _Settings_ tab heading located to the far right of the _Code_ heading.
2. Click the _Pages_ link located about half down the left side of the page under _Code and automation_.
3. Click the dropdown menu under _Source_ and ensure _Deploy from a branch_ is selected.
4. Click the two dropdown menus under _Branch_ and ensure _main_ and _/(root)_ are both selected respectively.  
RESULT: Your site will now be hosted and built from the README file created earlier. If these options were already selected, your site has already been built prior to this sequence.

This step relates to Andrew's comments on [_Resync_](https://rsync.samba.org/) and "_scripting your complexity away_". One thing to note is that Github is doing a lot of work behind the scenes to host this resume online. There are a lot of steps that future users and contributors will more than likely not want to go through. Instead, a script which automatically performs all the steps should be used and made available for all. Notice how this step only took a few clicks to perform; this is made possible by Github's numerous softwares and scripts being run without automatically.

### Step 4. Visit your website

## Customization

Customizing your GitHub Pages site can be simple or become incredibly complex. The reason being is that GitHub Pages uses Jekyll, a tool used to create static websites. How your site looks can be changed by using Jekyll, but alas, that won't be covered here. If you want to know more, check out the Jekyll tutorial in [More Resources](#more-resources).

## More Resources

- [Andrew Etter's _Modern Technical Writing: An Introduction to Software Documentation_](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Markdown tutorial](https://www.markdowntutorial.com/)
- [Jekyll tutorial](https://jekyllrb.com/tutorials/video-walkthroughs/)

## Authors and Acknowledgments

-This project uses the [Cayman Jekyll theme](https://github.com/pages-themes/cayman).

-Discussions in the README are based on the book, _Modern Technical Writing_ by Andrew Etter.

## FAQ

_Why is Markdown better than a word processor?_

- Markdown is better than word processors at making fast and legible documents. Markdown files are flexible that can be easily converted to other widely used file types including: XML, HTML, and JSON. Moreover, these file types can be easily rendered by websites without the required overhead when using DOCX or PDF file types.

_Why is my resume not showing up?_

- It can be a few things:
  - The filename of your resume must be either `index.md` or `README.md`. GitHub Pages prioritizes displaying `index.md`. If you want a README, your resume should be named `index.md`.
  - Ensure the GitHub Pages site is being built from the correct source branch on GitHub. This option can be found in the **GitHub Pages** section of your repository settings.
