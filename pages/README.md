# Shopify Test Application

This is a test application designed to showcase the creation of Shopify apps.

# Installation

1. Clone repo.
2. Install NPM package.
```
npm i
```
3. Login to Shopify Partner account.
4. From Apps -> Create App
5. Add API keys to '.env' file in root app directory.
6. Install ngrok globally. `npm i ngrok -g'  (may need to add write capability to install folder)

# Run Application

1. 'npm run dev' - Start Local Host
2. 'ngrok http 3000' - Start ngrok, which creates a tunnel to the local host with https.
3. In App Setup, update Shopify App URL and Allowed redirection URL.
    * https://xxxxxxxxxx.ngrok.io
    * https://xxxxxxxxxx.ngrok.io/auth/callback
