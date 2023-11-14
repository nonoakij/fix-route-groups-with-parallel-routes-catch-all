Minimal Repository to reproduce this issue: https://github.com/vercel/next.js/issues/58449
```shell
npm run build

> fix-route-groups-with-parallel-routes-catch-all@0.1.0 build
> next build

   ▲ Next.js 14.0.3-canary.7

Failed to compile.

app/(shop)/foo/page.tsx
You cannot have two parallel pages that resolve to the same path. Please check /(marketing)/@slot/[...catchAll]/page and /(shop)/foo/page. Refer to the route group docs for more information: https://nextjs.org/docs/app/building-your-application/routing/route-groups


> Build failed because of webpack errors
   Creating an optimized production build  .%   
```
