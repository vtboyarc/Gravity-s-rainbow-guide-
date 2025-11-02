# Gravity's Rainbow Guide

This repository hosts a static HTML guide that can be deployed as-is to any static host.

## Local preview

Open `index.html` in your browser to preview the site locally.

## Deploying to Vercel

1. Install the [Vercel CLI](https://vercel.com/docs/cli) and run `vercel login` if you have not already.
2. From the root of the project, run `vercel` and follow the prompts to create a new project or link an existing one.
3. Deploy updates with `vercel --prod` once you are satisfied with the preview deployment.

The repository includes a `vercel.json` configuration that serves the static `index.html` file for every request.
