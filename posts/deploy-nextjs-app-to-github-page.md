---
title: 'How to deploy next js app to github page'
date: '2023-12-26'
---

### Steps:

- Prepare your Next js app. Here I followd [Next.js quick start](https://www.nextjs.cn/learn/basics/create-nextjs-app) to create a blog.
- Push the project to Github.
- Followed the steps by [How to deploy a Nextjs app to GitHub pages](https://medium.com/frontendweb/how-to-deploy-a-nextjs-app-to-github-pages-1de4f6ed762e#:~:text=Steps%20for%20deploying%20nextjs%20on%20GitHub%20pages%20Go,Github%20action%2C%20you%20see%20the%20nextjs%20GitHub%20action.)

### Issues:

- Build error: next export has been removed in favor of "output": "export"
    1. There's no next.config.js in the blog App I created, so I first added [next.config.js](https://nextjs.org/docs/pages/building-your-application/deploying/static-exports). 
    2. Resolved the build error by [Github discussion](https://github.com/vercel/next.js/discussions/58790#discussioncomment-7655261).

### Remain issues:

- The profile avatar is not working yet.

