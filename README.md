# Promptopia

![ai_prompt_sharing](https://github.com/benjaminstratton/ai_prompt_sharing/blob/main/public/assets/images/thumbnail.png)

## Description

Welcome to the first-ever social media application for sharing creative and inspiring AI prompts!
* Created with Next.js and Tailwind.
* Includes server-side and client-side rendering for SEO optimization, Google authentication, a search feature, full CRUD, and more!

Check out the published project [here](https://ai-prompt-sharing-five.vercel.app/).

## Installation & Launch

To clone or fork the project from Github, follow [these](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop) instructions.

Afterward, use the package manager [npm](https://www.npmjs.com/) to install the dependencies.

```bash
npm install
```

Then, you will need to create a [dotenv](https://www.npmjs.com/package/dotenv) file (.env) within the root folder of the cloned/forked project and link you're [MongoDB](https://www.mongodb.com/docs/atlas/) database like so:

```javascript
MONGODB='mongodb+srv://<USERNAME>:<PASSWORD>@cluster0.jrgyfat.mongodb.net/restaurantfinder?retryWrites=true&w=majority'
```

Next, you will need to create environment variables for both the Google API and NextAuth.js. I will leave links below that go into more explanation for both:
* [Google API](https://cloud.google.com/apis/docs/getting-started)
* [NextAuth.js](https://next-auth.js.org/configuration/options)

Finally, launch the project!

```bash
npm run dev
```

## Usage

You can use this App to find new and inspiring ways your peers are using AI prompts! On the home page, you can click to sign in, search for a tag or username to view specific posts, and click on user profiles to be further inspired by someone's prompts. Once signed in, you can create your post by clicking the button on the home page. From there, you can click into your profile by clicking your user image where you will be able to view, edit, and delete your prompts.
