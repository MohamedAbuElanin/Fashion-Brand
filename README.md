# FASHION

An editorial fashion-store portfolio demo for a fictional contemporary Egyptian label.

## Run locally

```sh
npm install
npm run dev
```

Create a production bundle with `npm run build` and preview it with `npm run preview`.

## About the catalog

The 16 FASHION pieces, names, prices, colours, sizes, and stock counts are fictional showcase data in `src/catalog.ts`. Product imagery uses real fashion photography hosted by Unsplash. Images, Google Fonts, and Font Awesome load from their external services, so the preview needs an internet connection for those assets.

Cart and wishlist state are saved in local storage. Checkout is a demonstration flow: it does not submit an order or process payment. Size measurements and item details are illustrative.

Demo sign-in accepts any valid email and a password with 6 or more characters. It stores only the email as a local demo session; it does not authenticate against a server or save the password.
