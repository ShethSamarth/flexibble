# Flexibble (Dribbble Clone)

This is a repository for a Flexibble (Dribbble Clone): Next.js 13, React, TailwindCSS, Grafbase, GraphQL, Next Auth.

Key Features:

- Next Auth Authentication
- Implement Filtering Functionality
- Complete Pagination Capabilities
- Adding, Updating and Deleting Projects on Grafbase Database
- Image upload using Cloudinary
- Tailwind design for sleek UI
- Full responsiveness for all devices

# Final Version

To visit the website, [click here.](https://flexibble-grafbase.vercel.app)

### Cloning the repository

```shell
git clone https://github.com/ShethSamarth/flexibble.git
```

### Install packages

```shell
npm install
```

### Setup .env file at root

```js
NEXT_PUBLIC_GRAFBASE_API_URL=
NEXT_PUBLIC_GRAFBASE_API_KEY=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

NEXTAUTH_SECRET=
NEXTAUTH_URL=
NEXT_PUBLIC_SERVER_URL=

CLOUDINARY_NAME=
CLOUDINARY_KEY=
CLOUDINARY_SECRET=
```

### Setup .env file at root/grafbase

```js
NEXTAUTH_SECRET=
```

### Start the app

```shell
npx grafbase@0.24 dev

npm run dev
```
