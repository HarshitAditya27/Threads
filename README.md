<p align='center'><img src='' width="250" ></p>
<h1 align='center'> Threads</h1> 
<p align='center'>Deployed Link: https://threads-woad.vercel.app/  </p>

## Introduction 🐱‍💻
- Created Threads prototype using Next.js, React, and TypeScript. This prototype can perform creating users, posting a thread, creating communities, inviting members and posting threads via the community page, replying and commenting on threads and also getting activity updates on threads, and many more.
- Various tools such as <a href="https://clerk.com/">**Clerk**</a> is used for authentication and creating and using communities,  <a href="https://www.mongodb.com/">**MongoDB**</a> database for storing all kinds of data,  <a href="https://ui.shadcn.com/">**shadcn**</a> for enhancing UI components and  <a href="https://uploadthing.com/">**uploadthing**</a> for enabling file uploads in Next.js application. 

## Tech Stack used 👨‍💻

- **HTML**
- **TailwindCSS** 
- **TypeScript** 
- **MongoDB** 
- **Next.js**

## Features 🧰
- User **authentication** 👤.
- **Create** and **comments** on threads 💬
- Individual **user** and **community** bio page with the total number of threads, replies, members, etc.📄.
- **Edit** functionality for users and community ⚒️.
- **Storing** all thread data posted by users and the community 🫙.
- Mentioning **real date, time, and name of the community** when a user posts a thread as a member of a community ⌚.
- **Suggesting** users and communities for a user to see and join 🧑‍💻.
- Providing all **updates** on a thread by a user via the activity section 📰
- **Deleting** thread functionality 🗑️. 

## Learnings 📝
  
- Learned how to use varoius tools such as **Clerk**, **shadcn**, and **uploadthing** to implement various functionalities for creating real world application in Next.js. 
- Learned how to use **MongoDB** for storing and modifying data to produce correct and error-free results in deployed version of the application. 
  
## Installation 🛠️
  **Step 1**: Fork the repository. You can fork the repository by clicking on the fork button on the right-hand side below the profile.<br> 

  **Step 2**: Clone your forked repository. Replace **yourusername** with your GitHub Username. 
  
  ```
git clone "https://github.com/yourusername/Threads.git"
``` 
  **Step 3** : Go to the project folder and run npm i. It will install all the packages and dependencies used in the project. 
  
  ```
npm i
``` 
  **Step 4** : Run npm run dev. This will start the project in your local machine 🖥️.  
  
  ```
npm run dev
``` 
Hurray 🥳, you successfully deployed the project in your local machine 🎉.  

🚨But the app won't work because it will require **API keys** and **MongoDB database connection link** from various tools which are mentioned in **Setup .env file** section.

 ### Setup .env file

```js

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY= 
MONGODB_URL= 
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID= 
NEXT_CLERK_WEBHOOK_SECRET=
``` 
  ## Screenshots  


  ## Loved the project 💖? 
  
  If you found the project intresting then please do give this project a star ⭐. 
  <br> <br> <br>
   <p align="center" width="100%">
   Made with 💖 by Harshit Aditya   
</p>
