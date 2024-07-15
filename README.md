# Reclaim Protocol - js sdk 

This is a demo website that uses `@reclaimprotocol/js-sdk` to interact with the Reclaim protocol.


## Getting started

To get started, clone this repository and install the dependencies

### Install dependencies

```bash
npm install
```
### Set up environment variables

```bash
cp .env.example .env
```

Edit the `.env` file and set the `NEXT_PUBLIC_APP_ID` and `NEXT_PUBLIC_APP_SECRET` to the values you received from [Reclaim Developer Portal](https://dev.reclaimprotocol.org/).


### Update Provider IDs

Update the providerIds in `src/app/page.js` on [ine number 30 to the providerIds you received from [Reclaim Developer Portal](https://dev.reclaimprotocol.org/).

### Start the development server

```bash
npm run dev
```

The website will be available at [http://localhost:3000](http://localhost:3000)