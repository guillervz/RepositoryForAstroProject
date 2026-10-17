# Static Web Deployment in AWS with CI/CD Foundations

This project is a web application built with [Astro](https://astro.build/). It is the starting point for a project focused on static website deployment on AWS and CI/CD foundations.

## Prerequisites

* [Node.js](https://nodejs.org/) (LTS version recommended)
* npm (included with Node.js)
* Git

## Getting Started

### 1\. Clone the repository

```bash
git clone https://github.com/guillervz/RepositoryForAstroProject.git
cd RepositoryForAstroProject
```

### 2\. Install dependencies

```bash
npm install
```

### 3\. Start the development server

```bash
npm run dev
```

Open the local address displayed in the terminal. By default, Astro uses `http://localhost:4321/`. If `localhost` does not work, try `http://127.0.0.1:4321/`.

To stop the development server, press `Ctrl + C` in the terminal.

## Available Commands

|Command|Description|
|-|-|
|`npm run dev`|Starts the local development server|
|`npm run build`|Builds the application for production in `dist/`|
|`npm run preview`|Previews the production build locally|

## Project Structure

* `src/` — Application source files and pages
* `public/` — Static assets served directly
* `astro.config.mjs` — Astro configuration
* `package.json` — Project metadata, scripts, and dependencies
* `package-lock.json` — Records the installed dependency versions

## Current Status

The initial Astro application has been created, dependencies installed, and the local development server tested successfully.

Further work will extend this foundation toward static website deployment on AWS and CI/CD.

