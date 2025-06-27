# Gerador-Insta-Ia

This project is a web application to generate social media captions using AI. It is built with React, TypeScript, and Vite.

## Prerequisites

- [Node.js](https://nodejs.org/) and npm installed on your machine.

## Installation

```bash
npm install
```
Run this command in the `project` directory to install dependencies.

## Development

```bash
npm run dev
```
Starts the development server. Open `http://localhost:5173` in your browser to view the app.

## Build

```bash
npm run build
```
Produces a production build in the `dist` folder.

## Environment variables

Create a `.env` file in the `project` directory or copy the included `.env.example`.
It must define `VITE_WEBHOOK_URL` pointing to your webhook endpoint:

```bash
VITE_WEBHOOK_URL=https://example.com/your/webhook
```

