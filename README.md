# My Personal Blog

A personal blog built with [Astro](https://astro.build/), a modern static site generator optimized for content-focused websites.

## 🚀 Features

- ✅ Modern, clean design
- ✅ Markdown and MDX support
- ✅ Responsive layout
- ✅ Fast performance
- ✅ SEO-friendly
- ✅ RSS feed
- ✅ GitHub Pages deployment ready

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

## 🚀 Deployment

This blog is configured to be deployed to GitHub Pages. To deploy:

1. Update the `GITHUB_USERNAME` and `REPO_NAME` variables in `astro.config.mjs` with your GitHub username and repository name.
2. Push your code to the `main` branch of your GitHub repository.
3. Enable GitHub Pages in your repository settings, selecting the GitHub Actions option.
4. The GitHub Actions workflow will automatically build and deploy your site.

## 📝 Adding Content

To add a new blog post:

1. Create a new Markdown or MDX file in `src/content/blog/`
2. Add frontmatter with title, description, publication date, and hero image
3. Write your content using Markdown

Example:

```md
---
title: "My New Blog Post"
description: "A short description of the post"
pubDate: "Jul 22 2024"
heroImage: "/blog-placeholder-3.jpg"
---

# My New Blog Post

Content goes here...
```

## 🧪 Customization

- Update site title and description in `src/consts.ts`
- Customize the header and footer in `src/components/Header.astro` and `src/components/Footer.astro`
- Modify the homepage in `src/pages/index.astro`
- Update the About page in `src/pages/about.astro`

```sh
npm create astro@latest -- --template blog
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/blog)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/blog)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/blog/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![blog](https://github.com/withastro/astro/assets/2244813/ff10799f-a816-4703-b967-c78997e8323d)

Features:

- ✅ Minimal styling (make it your own!)
- ✅ 100/100 Lighthouse performance
- ✅ SEO-friendly with canonical URLs and OpenGraph data
- ✅ Sitemap support
- ✅ RSS Feed support
- ✅ Markdown & MDX support

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
├── public/
├── src/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── README.md
├── package.json
└── tsconfig.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

The `src/content/` directory contains "collections" of related Markdown and MDX documents. Use `getCollection()` to retrieve posts from `src/content/blog/`, and type-check your frontmatter using an optional schema. See [Astro's Content Collections docs](https://docs.astro.build/en/guides/content-collections/) to learn more.

Any static assets, like images, can be placed in the `public/` directory.

## 👀 Want to learn more?

Check out [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## Credit

This theme is based off of the lovely [Bear Blog](https://github.com/HermanMartinus/bearblog/).
