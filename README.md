# facebook-firebase-next-chat

# 🚀 Javascript full-stack 🚀

https://github.com/coding-to-music/facebook-firebase-next-chat

https://facebook-firebase-next-chat.vercel.app

By Hiep Le https://github.com/cometchat-pro-tutorials/facebook-clone

https://github.com/cometchat-pro-tutorials/facebook-clone

https://www.cometchat.com/tutorials/how-to-build-a-social-networking-site-with-next-js-facebook-clone

## Environment Values

```java
const firebaseConfig = {
  apiKey: `${process.env.NEXT_PUBLIC_FIREBASE_API_KEY}`,
  authDomain: `${process.env.NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN}`,
  databaseURL: `${process.env.NEXT_PUBLIC_FIREBASE_DATABASE_URL}`,
  projectId: `${process.env.NEXT_PUBLIC_FIREBASE_PROJECT_ID}`,
  storageBucket: `${process.env.NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET}`,
  messagingSenderId: `${process.env.NEXT_PUBLIC_FIREABSE_MESSAGING_SENDER_ID}`,
  appId: `${process.env.NEXT_PUBLIC_FIREBASE_APP_ID}`,

        appId: `${process.env.NEXT_PUBLIC_COMETCHAT_APP_ID}`,
        apiKey: `${process.env.NEXT_PUBLIC_COMETCHAT_API_KEY}`,

              cometChat.login(user.id, `${process.env.NEXT_PUBLIC_COMETCHAT_AUTH_KEY}`).then(

  const initCometChat = async () => {
    const { CometChat } = await import('@cometchat-pro/chat');
    const appID = `${process.env.NEXT_PUBLIC_COMETCHAT_APP_ID}`;
    const region = `${process.env.NEXT_PUBLIC_COMETCHAT_REGION}`;
    const appSetting = new CometChat.AppSettingsBuilder().subscribePresenceForAllUsers().setRegion(region).build();

```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/facebook-firebase-next-chat.git
git push -u origin main
vercel --prod --confirm

# vercel env add
```

# How to Build a Social Networking Site with Next.js (Facebook Clone)

Read the full tutorial here: [**>> How to Build a Social Networking Site with Next.js (Facebook Clone)**](https://www.cometchat.com/tutorials/#)

This example shows How to Build a Social Networking site with Next.js (Facebook Clone):

![Facebook Clone](./screenshots/0.gif)

<center><figcaption>Facebook Clone</figcaption></center>

## Technology

This demo uses:

- CometChat Pro 2.4.0
- Firebase
- Next.js
- React.js
- Uuid
- Validator

## Running the demo

To run the demo follow these steps:

1. [Head to CometChat Pro and create an account](https://app.cometchat.com/signup)
2. From the [dashboard](https://app.cometchat.com/apps), add a new app called **"facebook-clone"**
3. Select this newly added app from the list.
4. From the Quick Start copy the **APP_ID, APP_REGION and AUTH_KEY**. These will be used later.
5. Also copy the **REST_API_KEY** from the API & Auth Key tab.
6. Navigate to the Users tab, and delete all the default users and groups leaving it clean **(very important)**.
7. Download the repository [here](https://github.com/hieptl/facebook-clone/archive/main.zip) or by running `git clone https://github.com/hieptl/facebook-clone.git` and open it in a code editor.
8. [Head to Firebase and create a new project](https://console.firebase.google.com)
9. Create a file called **.env.local** in the root folder of your project.
10. Import and inject your secret keys in the **.env.local** file containing your CometChat and Firebase in this manner.

```js
NEXT_PUBLIC_FIREBASE_API_KEY = xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN =
  xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
NEXT_PUBLIC_FIREBASE_DATABASE_URL =
  xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
NEXT_PUBLIC_FIREBASE_PROJECT_ID = xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET =
  xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
NEXT_PUBLIC_FIREABSE_MESSAGING_SENDER_ID =
  xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
NEXT_PUBLIC_FIREBASE_APP_ID = xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;

NEXT_PUBLIC_COMETCHAT_APP_ID = xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
NEXT_PUBLIC_COMETCHAT_REGION = xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
NEXT_PUBLIC_COMETCHAT_AUTH_KEY = xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
NEXT_PUBLIC_COMETCHAT_API_KEY = xxx - xxx - xxx - xxx - xxx - xxx - xxx - xxx;
```

11. Make sure to exclude **.env.local** in your gitIgnore file from being exposed online.
12. Run the following command to install the app.

```sh
    npm install
    npm run dev
```

Questions about running the demo? [Open an issue](https://github.com/hieptl/facebook-clone/issues). We're here to help ✌️

## Useful links

- 🏠 [CometChat Homepage](https://app.cometchat.com/signup)
- 🚀 [Create your free account](https://app.cometchat.com/apps)
- 📚 [Documentation](https://prodocs.cometchat.com)
- 👾 [GitHub](https://www.github.com/cometchat-pro)
- 🔥 [Firebase](https://console.firebase.google.com)
- 🔷 [Next.js](https://nextjs.org/)
- ✨ [Live Demo](https://vercel-facebook-clone.vercel.app)
