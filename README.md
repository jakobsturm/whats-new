# Hello Eleventy!

This project is a blog powered by [Eleventy](https://www.11ty.dev/), a lightweight static site generator. That means you get all the power of a server-side framework but it builds plain HTML files for fast loading by your visitors. This project includes some default posts and layouts you can use as a foundation, and you can customize how your site builds in the JavaScript code. π

## Prerequisites

You'll get best use out of this project if you're familiar with basic HTML and JavaScript. This is a static site, which means the server builds it using the content of the `src` folder, then is able to serve it to your users quickly. The posts are in Markdown, which is similar to HTML (markup) but with a lot less syntax!

## What's in this project?

β `README.md`: Thatβs this file, where you can tell people what your cool website does and how you built it.

β `public/style.css`: The styling rules for your pages and posts.

β `.eleventy.js`: Here you can configure how Eleventy builds your content into the site. Read through the initial blog posts in the site for steps on extending this code.

β `package.json`: Your project's dependencies, where you will also find the start command to run eleventy.

β `src/`: This folder contains all the files Eleventy will use to build your site.

### Working in the `src/` folder π

β `index.md`, `posts.md`, `about.md`: These Markdown files include the content for your Home, Posts, and About pages.

β `posts/`: These are the Markdown files for the posts that make up your blogβyou can add new posts here and remove any you don't want. Each one includes front matter that Eleventy uses to build the content into the site, passing the data into the template referenced as `layout` at the top of the file.

β `_includes/layouts/`: This is where all of your page level layouts go. The **\_** tells you that this is an _eleventy only_ folder. Each layout uses [Nunjucks](https://mozilla.github.io/nunjucks/templating.html) to build the page or post data into an HTML page. There is one base layout that all others extend.

β `seo.json`: When you're ready to share your new site or add a custom domain, change SEO/meta settings in here.
