# Multi-Platform Google Proxy

[![Documentation](https://img.shields.io/badge/Documentation-%F0%9F%93%9A-brightgreen)](https://yourname.github.io/yourrepo/)
[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Deployed-brightgreen)](https://yourname.github.io/yourrepo/)

A multi-platform reverse proxy solution for Google with login page redirection to gov.cn.

## One-Click Deployment

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/yourname/yourrepo)

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/yourname/yourrepo&env=MAIN_DOMAIN)

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yourname/yourrepo)

[![Deploy Vite App](https://img.shields.io/badge/Deploy_Vite_App-%23646CFF?logo=vite&logoColor=white)](https://app.netlify.com/start/deploy?repository=https://github.com/yourname/yourrepo-vite)

[![Deploy to GitLab](https://gitlab.com/gitlab-org/gitlab/-/raw/master/app/assets/images/deploy_buttons/deploy_to_gitlab.svg)](https://gitlab.com/projects/new#import-project)

## Documentation

Access the full documentation in your preferred language:

- [🇨🇳 简体中文](https://yourname.github.io/yourrepo/zh-CN/index.html)
- [🇹🇼 繁體中文](https://yourname.github.io/yourrepo/zh-TW/index.html)
- [🇺🇸 English](https://yourname.github.io/yourrepo/en-US/index.html) (AI Translated)
- [🇷🇺 Русский](https://yourname.github.io/yourrepo/ru-RU/index.html) (AI Translated)

## GitLab Deployment Guide

### Environment Variables
```env
# Required
MAIN_DOMAIN=yourdomain.com
TARGET_ROOT=google.com
REDIRECT_URL=https://gov.cn

# Optional (for auto-deployment to other platforms)
CLOUDFLARE_API_TOKEN=your_api_token
VERCEL_TOKEN=your_vercel_token
NETLIFY_AUTH_TOKEN=your_netlify_token
NETLIFY_SITE_ID=your_netlify_site_id