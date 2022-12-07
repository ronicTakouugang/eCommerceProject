This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started
Using your terminal and the command cd, enter the project's root which in this case is "eCommerceProject"

  - Use the command npm install --legacy-peer-deps to install all the dependencies necessary for this eCommerceProject

## Installing Sanity
This projects includes sanity(https://www.sanity.io/) that you should install before continuing; Run the following commands:

  - npm install -g @sanity/cli to install Sanity
  
  - sanity start
  
 Here you will be asked to create a Sanity account, with that done you may see our 'Desk' with the product and banner components. Modify it as your will
 to change informations on our the Website.
* Use the command sanity manage to open the sanity project management UI

Open API in the Menu bar, go at the bottom and Create an API TOKEN

In the .env file found in our poroject replace : 

-> NEXT_PUBLIC_SANITY_TOKEN = '' with your own Token

You will see a ProjectID at the top of the Dashboard.

In the client.js replace :

projectId = '' with your own projectID

##Instaling Stripe for the payments

Create a Stripe account. 

-> NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY = '' with your Publishable key
-> STRIPE_SECRET_KEY = ''

Now, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.


