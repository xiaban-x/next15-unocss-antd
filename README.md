This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
推荐使用 bun 启动
如果还未下载 bun，请参考[https://bun.sh/docs/installation](https://bun.sh/docs/installation)

## Introduce
这是一个整合了`Nextjs15`、`UnoCSS`、`Antd`的模板项目，同时使用到了`UnoCSS`的 `Attributify Preset` 写法

需要注意的是，该模板中使用的是`React 18`版本，由于`React 19`调整了`react-dom`的导出方式，
导致 antd 无法直接使用 ReactDOM.render 方法，导致 antd 部分功能无法正常使用，
同时也导致了很多包对`React 19`的兼容度还不够，但是 `Nextjs15`的许多新特性又还不错，例如 `turbopack`稳定了，
因此才采用了`Nextjs15`+`React 18`的组合

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
