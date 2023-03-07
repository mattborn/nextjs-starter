# nextjs-starter

## Next.js 13

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Dev locally

First, run the development server:

```bash
npm run dev
```

## Second commit cleanup

The exact steps that deviate from the `create-next-app` command:

Delete the SVGs.

```
rm public/*
```

Clear the stylesheets.

```
true > src/app/globals.css && true > src/app/page.module.css
```

Gut the components.

> Do this manually for `src/app/page.js`

## Intentionally excluded

Entrepreneurs with short runways don’t have time for these things. There are solid arguments for having them when you have long runways.

- ESLint
- Jest
- Storybook + Chromatic
- Tailwind
- TypeScript
