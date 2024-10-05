# ETH Telegram Mini App 

The project follows a standard directory structure for a Next.js application. Here's an overview:

```
.
├── README.md
├── components.json
├── jsconfig.json
├── next-env.d.ts
├── next.config.js
├── package-lock.json
├── package.json
├── postcss.config.js
├── public
│   ├── arbitrum.svg
│   ├── arrow.svg
│   ├── butterfly.svg
│   ├── loader.svg
│   └── rabble.svg
├── src
│   ├── app
│   │   ├── contract
│   │   │   └── page.jsx
│   │   ├── favicon.ico
│   │   ├── globals.css
│   │   ├── layout.jsx
│   │   └── page.jsx
│   ├── assets
│   │   └── Arrow.jsx
│   ├── components
│   │   ├── ErrorBoundary.jsx
│   │   ├── ErrorPage.jsx
│   │   ├── Popup.jsx
│   │   ├── shared
│   │   │   └── Navbar.jsx
│   │   └── ui
│   │       ├── button.jsx
│   │       ├── input.tsx
│   │       └── sonner.tsx
│   ├── constants
│   │   ├── abi.js
│   │   └── index.js
│   ├── containers
│   │   ├── contract
│   │   │   ├── ReadContract.jsx
│   │   │   └── WriteContract.jsx
│   │   └── home
│   │       └── Profile.jsx
│   ├── hooks
│   │   ├── useClientOnce.js
│   │   ├── useDidMount.js
│   │   └── useTelegramMock.js
│   ├── lib
│   │   └── utils.js
│   ├── providers
│   │   ├── Layout.jsx
│   │   ├── TelegramProvider.jsx
│   │   └── Web3Provider.jsx
│   └── utils
│       └── config.js
└── tailwind.config.js
```
