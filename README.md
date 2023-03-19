This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

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


## Install Tailwind
[Read](https://tailwindcss.com/docs/guides/nextjs) the documentation on the Tailwind Next.js installation

`npm install -D tailwindcss postcss autoprefixer`

`npx tailwindcss init -p` 

## Working Next Project
![image](https://user-images.githubusercontent.com/83961643/225888840-39b1bf4f-3a30-4d3a-a88d-fdd10771df58.png)

## Deleting the standard template to play with Tailwind
Creating Hello world to play with in styling 
![image](https://user-images.githubusercontent.com/83961643/225898616-4129beec-934b-4969-becb-dae63f668b90.png)

## [TAILWIND DOCUMENTATION](https://tailwindcss.com/docs/installation)
- [Configuration](https://tailwindcss.com/docs/configuration) 
- [Preflight](https://tailwindcss.com/docs/preflight)
- [Layout](https://tailwindcss.com/docs/aspect-ratio)
- [Flexbox & grid](https://tailwindcss.com/docs/flex-basis)
- [Spacing](https://tailwindcss.com/docs/padding)
- [Sizing](https://tailwindcss.com/docs/width)
- [Typrography](https://tailwindcss.com/docs/font-family)
- [Backgrounds](https://tailwindcss.com/docs/background-attachment)
- [Borders](https://tailwindcss.com/docs/border-radius)
- [Effects](https://tailwindcss.com/docs/box-shadow)
- [Filters](https://tailwindcss.com/docs/blur)
- [Tables](https://tailwindcss.com/docs/border-collapse)
- [Transitions & Animation](https://tailwindcss.com/docs/transition-property)
- [Transforms](https://tailwindcss.com/docs/scale)
- [Interactivity](https://tailwindcss.com/docs/accent-color)
- [SVG](https://tailwindcss.com/docs/fill)
- [Accessibility](https://tailwindcss.com/docs/screen-readers)
- [OFFICIAL PLUGINS](https://tailwindcss.com/docs/typography-plugin)

## Playing around with changing the project with Tailwind 
Trying out different styling - Adding my own custom colors
![image](https://user-images.githubusercontent.com/83961643/225907434-de389832-275b-42f3-ac3e-171be85188aa.png)
In the tailwind.config file you add your colors in the extend section. If you don't you override the tailwind styling library.
![image](https://user-images.githubusercontent.com/83961643/226188864-c71f1fbd-b4f4-4459-aca0-0155c583bd8d.png)


Adding a border and custom colours 
![image](https://user-images.githubusercontent.com/83961643/226188772-f27beb9c-7319-48fb-9a65-ae74dd5ee801.png)

You can create your own custom plugins to add into your websites. 

You can add tailwind custome styles directly in your class like this 
` bg-[#bada55]`
![image](https://user-images.githubusercontent.com/83961643/226196780-f4bfad48-0e1c-4dac-8e5b-7ad59d638673.png)

If you want to override, have more contorl/POWER you can use the `@layers` directive to add styles to Tailwind's `base` `components` and `utilities` 
You do this in the Global.css file 

``` 
@layer utilities {
  .bg-brand-gradient { /* ... */ }
}
```
![image](https://user-images.githubusercontent.com/83961643/226197761-ba5b3740-dda1-4947-8e75-af8ca6e4a699.png)
![image](https://user-images.githubusercontent.com/83961643/226197781-7bea8ad7-1a7c-4ed7-8742-ae5962c19ff8.png)

You can also chain the classes in the `@apply` in `@layer` when you clear the classes on your `page.tsx` file 
![image](https://user-images.githubusercontent.com/83961643/226198098-ebbf0878-2dec-4139-854c-712d37ba60e0.png)

You can use multiple CSS files and you can mention them in the `postcss.config.js` file in the plugins section. 
Plugins are your javascript functions which help you write CSS in js.

## Typography 
So we can see the headers are the same size 
We need to manually change these elements
![image](https://user-images.githubusercontent.com/83961643/226199209-23108181-11e0-4848-9dd4-0f34c4aeb732.png)
Now we can see some styling to the p tag:
![image](https://user-images.githubusercontent.com/83961643/226199272-de832c29-e776-44e8-b094-44107d4a9ebc.png)


