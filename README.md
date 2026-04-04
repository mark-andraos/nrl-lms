# NRL Last Man Standing — Deployment Guide

## Files
- `index.html` — the entire app
- `manifest.json` — makes it installable as a PWA
- `vercel.json` — Vercel routing config

## Deploy to Vercel (step by step)

### 1. Create a GitHub account
Go to https://github.com and sign up (free).

### 2. Create a new repository
- Click the + icon → New repository
- Name it: nrl-lms
- Set to Public
- Click Create repository

### 3. Upload the files
- Click "uploading an existing file"
- Drag all 3 files (index.html, manifest.json, vercel.json) into the upload area
- Click "Commit changes"

### 4. Deploy to Vercel
- Go to https://vercel.com and sign up with your GitHub account
- Click "Add New Project"
- Select your nrl-lms repository
- Click Deploy (no settings needed)
- Wait ~30 seconds
- Your app is live at https://nrl-lms.vercel.app (or similar)

### 5. Share the link
Send the Vercel URL to your players. They enter their email to sign in.

## Admin
Sign in with andraos1992@gmail.com to see admin controls for managing results.

## Updating the app
Whenever you change index.html on GitHub, Vercel automatically redeploys within 30 seconds.
