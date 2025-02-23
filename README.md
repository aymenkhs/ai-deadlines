---
title: AI Deadlines
emoji: ⚡
colorFrom: gray
colorTo: blue
sdk: docker
pinned: false
---

# AI Conference Deadlines

## Project info

This project is entirely based on the awesome http://aideadlines.org/. It's an up-to-date version along with a new UI.

It was bootstrapped using [Lovable](https://lovable.dev/) and [Cursor](https://www.cursor.com/).

**URL**: https://huggingface.co/spaces/huggingface/ai-deadlines

## How to run locally

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone https://github.com/NielsRogge/ai-deadlines-hub

# Step 2: Navigate to the project directory.
cd ai-deadlines-hub

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

## Deploy with Docker

First build the Docker image as follows:

```bash
docker build -t ai-deadlines .
```

Next it can be run as follows:

```bash
docker run -it -p 7860:7860 ai-deadlines
```

## Technologies used

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
