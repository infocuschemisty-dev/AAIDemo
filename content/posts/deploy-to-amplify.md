---
title: "Deploying to AWS Amplify"
date: 2023-10-27
description: "How to deploy this Hugo site to the cloud in minutes."
params:
    icon: "☁️"
---

Deploying your Hugo site to AWS Amplify is incredibly simple.

## Steps

1. **Push to Code**: Commit your changes and push this repository to GitHub, GitLab, or Bitbucket.
2. **Connect Amplify**: 
   - Go to AWS console.
   - Select AWS Amplify.
   - "New App" > "Host web app".
   - Connect your repository.
3. **Build Settings**: Amplify will auto-detect Hugo. Use the `amplify.yml` included in this repo.
4. **Deploy**: Click "Save and Deploy".

## Why Amplify?

- Continuous Deployment (CD) out of the box.
- Global CDN for fast delivery.
- Feature branching and pull request previews.

Your site will be live at `https://master.unique-id.amplifyapp.com` or your custom domain!
