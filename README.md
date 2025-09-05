# Honorio Taveras — SRE / DevOps Portfolio

[![Build & Deploy](https://github.com/HonorioTaveras/sre-portfolio/actions/workflows/hugo.yaml/badge.svg)](https://github.com/HonorioTaveras/sre-portfolio/actions/workflows/hugo.yaml)
[![Uptime Status](https://img.shields.io/uptimerobot/status/m801305553-bb2b4eed688a89bdf41bebb7?label=Website%20Uptime&style=flat-square)](https://stats.uptimerobot.com/SqEb9VLsdK)
[![Uptime 30d](https://img.shields.io/uptimerobot/ratio/m801305553-bb2b4eed688a89bdf41bebb7?label=Uptime%20Last%2030d)](https://stats.uptimerobot.com/SqEb9VLsdK)

Live site: **https://honoriotaveras.com**

A fast, Hugo-powered personal site using the **Adritian Free** theme. Built on push with GitHub Actions and served via GitHub Pages.

## Features
- Hugo + Adritian theme (Bootstrap 5, dark/light)
- Custom sections: Home, About, Experience, Skills, Contact
- CI/CD with GitHub Actions (cache, minify, extended Hugo)
- Custom domain + HTTPS

## Local development
```bash
# prerequisites: Hugo Extended, Node.js (to build theme assets)
npm install          # installs Bootstrap and theme deps
hugo server -D       # http://localhost:1313
