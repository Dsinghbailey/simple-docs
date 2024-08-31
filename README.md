# Simple Docs

This is a repo for a simple documentation site. Used by [namestone docs](https://namestone.xyz/docs)

## Editing

All the content Files are located in the data folder.  
`[[slug]].js` is where all the formatting is handled  
Edit the siteMetaData to get Correct SEO information  
Make sure if you add files you also edit the site maps at the top of slug.js

## Run Dev

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
