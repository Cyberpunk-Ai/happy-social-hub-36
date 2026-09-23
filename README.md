# Spaces1

Spaces1 is a creator social network: posts and stories, live audio spaces, direct
messages and calls, tips with transparent platform fees, and an admin console.

Built with [Lovable](https://lovable.dev) on TanStack Start (React 19, Vite,
Tailwind CSS v4) with Lovable Cloud for database, auth, storage and server
functions.

## Local development

```sh
bun install
bun run dev
```

## Configuration

All tunables live in `src/lib/config.ts` and read `VITE_*` environment
variables, including brand name, AI model ids, feed page sizes, upload limits
and feature flags. Platform fee percentages are configurable via
`VITE_PLATFORM_FEE_FREE`, `VITE_PLATFORM_FEE_PLUS` and `VITE_PLATFORM_FEE_PRO`.

No card, bank or wallet details are ever stored by the app — payments and
payouts stay with the payment provider.
