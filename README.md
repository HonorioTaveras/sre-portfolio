# Honorio Taveras — SRE / DevOps Portfolio

[![Build & Deploy](https://github.com/HonorioTaveras/sre-portfolio/actions/workflows/hugo.yaml/badge.svg)](https://github.com/HonorioTaveras/sre-portfolio/actions/workflows/hugo.yaml)

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
