## Tạo môi trường env

```
PRIVATE_KEY=0000000000000000000000000000000000000000000000000000000000000000
RPC_URL=https://rpc.ankr.com/eth_goerli
COOLDOWN_HOURS=2
VALUE=1230000000000000
NEXT_PUBLIC_HCAPTCHA_SITE_KEY=00000000-0000-0000-0000-000000000000
HCAPTCHA_SECRET=0x0000000000000000000000000000000000000000
REDIS_URI=redis://default:key@url.com:6379
```

## Hướng dẫn chi tiết

PRIVATE_KEY: The private key of the wallet issuing funds. https://metamask.zendesk.com/hc/en-us/articles/360015289632

RPC_URL: RPC url of the blockchain https://www.ankr.com/rpc/

COOLDOWN_HOURS: Amount of hours users must wait to recieve funds again

VALUE: Value in smallest unit (ie: wei) https://eth-converter.com/

NEXT_PUBLIC_HCAPTCHA_SITE_KEY: Create hCaptcha account. Also known as `Sitekey` https://dashboard.hcaptcha.com/sites

HCAPTCHA_SECRET: Create hCpatcha account. Also known as `Secret Key` https://dashboard.hcaptcha.com/settings

REDIS_URI: Redis is an in-memory key-value database. https://redis.com/redis-enterprise-cloud/overview/

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
