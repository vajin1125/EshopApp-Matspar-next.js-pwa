# Matspar Company Tech task

## Design
[Figma Design](https://www.figma.com/file/YnmPEsSSwgUGuU4djuRdJK/MS-React-developer-test?node-id=23%3A142)
![](./Screenshot_2.png)

I have build this project for technical test

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Result
![Screenshot_4](https://user-images.githubusercontent.com/31552910/219813240-61e15c08-8981-4eae-9308-6b89d8e9c8e4.png)
![Screenshot_1](https://user-images.githubusercontent.com/31552910/219813253-b8eb908e-765a-4e60-843f-3bf1501868f4.png)
![Screenshot_2](https://user-images.githubusercontent.com/31552910/219813266-c7123450-52b9-4da3-aedb-587d35af9e20.png)
![Screenshot_3](https://user-images.githubusercontent.com/31552910/219813272-bebd7b44-a44e-42ba-accc-2bf85bc95ab5.png)


## Development

### Fetch API
if you fetch api on frontend, CORS error appear.
you have to fetch api on backend

### API

#### Get Products
https://api.matspar.se/slug

Post Request Body

{

        slug : "/kategori",

        query : {"q" : req.body.Squery}
}

#### Get search suggestions

https://api.matspar.se/autocomplete?query=

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
