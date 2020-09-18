---
title: 'Preview Deployment for Every Push'
date: '2020-09-18'
---

After deploying to Vercel, try doing the following if you can:

* Create a new branch on your app.
* Make some changes and push to GitHub.
* Create a new pull request (GitHub help page).
* You should see a comment by the **vercel** bot on the pull request page.

![](https://nextjs.org/static/images/learn/deploying-nextjs-app/vercel-bot.png)

Try clicking on the Preview URL inside this comment. You should see the changes you just made.

When you have a pull request open, Vercel automatically creates a preview deployment for that branch on every push. The preview URL will always point to the latest preview deployment.

You can share this preview URL with your collaborators and get immediate feedback.

If your preview deployment looks good, merge it to **master**. When you do this, Vercel automatically creates a production deployment.
