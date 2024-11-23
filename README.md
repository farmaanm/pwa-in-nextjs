# Next.js PWA

## 1. Install dependencies

```bash
npm install next-pwa
```

## 2. Add to next.config.mjs

```js
import withPWA from 'next-pwa';

export default withPWA({
    dest: "public",
    register: true,
    skipWaiting: true,
});
```

## 3. Run the project

```bash
npm run dev
```
