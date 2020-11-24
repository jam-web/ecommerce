# Commerce.js React Product Listing and Cart

Product listing page with cart functionalities using Commerce.js and React.

**Note**
- This app is built using [Commerce.js](https://commercejs.com/) v2 SDK

## Overview

This README will guide you in getting up and running with a this project.## Prerequisites

- IDE or code editor of your choice
- Node (v8.2.0 or higher)
- NPM or Yarn
- Chec CLI `yarn global add @chec/cli`

## Setup

### Create a Chec account. 

Now that you’ve installed Chec CLI globally, you will be able to access the list of `chec [COMMANDS]`, one of which is registering for a Chec account. Let’s go ahead and get that set up!

```bash
# Open the Chec registration page in your browser
chec register
```

Follow the rest of the walk-through to set up your merchant details. Alternatively, you can go [here](https://authorize.chec.io/signup) to register for a Chec account. 

**STEP 1.** Clone the repo and install dependencies

```bash
# Clone the repository locally, optionally rename the repo, change into the directory
git clone https://github.com/chec/commercejs-react-functional.git chec-store 
# Change into the directory and install dependencies
cd chec-store && yarn
```

**STEP 2.** Set up your environment variables

Replace the sample `.env.example` dotenv file at the root of the project to store your Chec `public_key`.

```bash
# Copy from source file to destination file .env
cp .env.example .env
```

You can access your API key under in your Chec dashboard setup, then navigate to the Develop tab to copy your Public Key and Secret Key. Replace the provided `CHEC_PUBLIC_KEY` with your own key.

```js
// .env

# Fill in your public key and secret key
CHEC_PUBLIC_KEY=
CHEC_API_URL=https://api.chec.io
NODE_ENV=
```

This file is meant to not be committed to source control and also will be hidden in file browsers.

**STEP 3.** Run development environment
```bash
# Run your development environment on http://localhost:3000
yarn start
```

Now head on over to http://localhost:3000 after starting your development to view the application!

**STEP 4.** Make any necessary changes you need and push the code to a repository on Github or your choice of platform.

## 🥞 Stack

- Framework - [React.js](https://reactjs.org)
- eCommerce - [Chec/Commerce.js](https://commercejs.com)
- Styling - [Bootstrap](https://getbootstrap.com) and [SASS](https://sass-lang.com)

