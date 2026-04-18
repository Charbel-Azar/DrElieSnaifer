# Dr. Elie Snaifer - Breast Health Guide

Patient-facing website for Dr. Elie Snaifer, Assistant Professor of Clinical OB-GYN and director of the Snaifer Fertility Center. Provides breast health information, screening guidelines, and a WhatsApp link to book a consultation.

Live at https://snaiferfertilitycenter.vercel.app

## What it is

A single-page static website. All content lives in `index.html` with supporting styles, scripts, and images under `assets/`. Content is available in English, Arabic, and French.

## Stack

Plain HTML, CSS, and vanilla JavaScript. No build step. Deployed on Vercel.

## Running locally

Open `index.html` directly in a browser, or run `vercel dev` from the project root if the Vercel CLI is installed.

## Deploying

Run `vercel --prod` to push to production. The Vercel project is linked via the `.vercel/` folder.

## Files

- `index.html` is the full site
- `assets/` contains CSS, JavaScript, and images
- `vercel.json` is the hosting config
- `package.json` holds project metadata
