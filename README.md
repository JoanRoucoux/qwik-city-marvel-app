# Qwik City Marvel App

This application allows you to discover Marvel comics and characters.

Don't forget to add a `.env.local` file if you want to try it:
```
VITE_MARVEL_PUBLIC_API_KEY=XXXX
VITE_MARVEL_PRIVATE_API_KEY=YYYY
```

## Stack
| Client | API |
| ------------- | ------------- |
| Qwik | Marvel API |

## Demo
<div>
    <img width="400" alt="qwik-city-marvel-app_home" src="https://github.com/JoanRoucoux/qwik-city-marvel-app/assets/21682157/a5ebd157-24fb-44bd-856e-2277c4c03303">
    <img width="400" alt="qwik-city-marvel-app_search" src="https://github.com/JoanRoucoux/qwik-city-marvel-app/assets/21682157/5292766b-6fad-400a-bdf0-5eec0b57252f">
    <img width="400" alt="qwik-city-marvel-app_comic" src="https://github.com/JoanRoucoux/qwik-city-marvel-app/assets/21682157/fde83788-1ac9-4dbc-b078-9e944552b94b">
    <img width="400" alt="qwik-city-marvel-app_character" src="https://github.com/JoanRoucoux/qwik-city-marvel-app/assets/21682157/83384dec-e837-442f-a463-33986cc40618">
</div>

# Qwik City App ⚡️

- [Qwik Docs](https://qwik.builder.io/)
- [Discord](https://qwik.builder.io/chat)
- [Qwik GitHub](https://github.com/BuilderIO/qwik)
- [@QwikDev](https://twitter.com/QwikDev)
- [Vite](https://vitejs.dev/)

---

## Project Structure

This project is using Qwik with [QwikCity](https://qwik.builder.io/qwikcity/overview/). QwikCity is just a extra set of tools on top of Qwik to make it easier to build a full site, including directory-based routing, layouts, and more.

Inside your project, you'll see the following directory structure:

```
├── public/
│   └── ...
└── src/
    ├── components/
    │   └── ...
    └── routes/
        └── ...
```

- `src/routes`: Provides the directory based routing, which can include a hierarchy of `layout.tsx` layout files, and an `index.tsx` file as the page. Additionally, `index.ts` files are endpoints. Please see the [routing docs](https://qwik.builder.io/qwikcity/routing/overview/) for more info.

- `src/components`: Recommended directory for components.

- `public`: Any static assets, like images, can be placed in the public directory. Please see the [Vite public directory](https://vitejs.dev/guide/assets.html#the-public-directory) for more info.

## Add Integrations and deployment

Use the `npm run qwik add` command to add additional integrations. Some examples of integrations include: Cloudflare, Netlify or Express server, and the [Static Site Generator (SSG)](https://qwik.builder.io/qwikcity/guides/static-site-generation/).

```shell
npm run qwik add # or `yarn qwik add`
```

## Development

Development mode uses [Vite's development server](https://vitejs.dev/). During development, the `dev` command will server-side render (SSR) the output.

```shell
npm start # or `yarn start`
```

> Note: during dev mode, Vite may request a significant number of `.js` files. This does not represent a Qwik production build.

## Preview

The preview command will create a production build of the client modules, a production build of `src/entry.preview.tsx`, and run a local server. The preview server is only for convenience to locally preview a production build, and it should not be used as a production server.

```shell
npm run preview # or `yarn preview`
```

## Production

The production build will generate client and server modules by running both client and server build commands. Additionally, the build command will use Typescript to run a type check on the source code.

```shell
npm run build # or `yarn build`
```
