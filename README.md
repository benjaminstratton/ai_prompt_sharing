# Promptopia

## Description

Welcome to the first-ever social media application for sharing creative and inspiring AI prompts!
* Created with Next.js and Tailwind.
* Includes Google authentication, a search feature, full CRUD, and more!

Check out the published project [here](https://ai-prompt-sharing-five.vercel.app/).

## Installation & Launch

To clone or fork the project from github, follow [these](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop) instructions.

Afterward, use the package manager [npm](https://www.npmjs.com/) to install the dependencies.

```bash
npm install
```

Then, you will need to create a [dotenv](https://www.npmjs.com/package/dotenv) file (.env) within the root folder of the cloned/forked project and link your [MongoDB](https://www.mongodb.com/docs/atlas/) database like so:

```javascript
MONGODB='mongodb+srv://<USERNAME>:<PASSWORD>@cluster0.jrgyfat.mongodb.net/restaurantfinder?retryWrites=true&w=majority'
```

Finally, launch the project!

```bash
node index.js
# Or
nodemon
```

## Usage

You can use this App to find the best restaurants in the world, by choosing one of the displayed cities. Once you are on the city page, you can add a new data (a restaurant). If you want to edit or delete the current data, click into a specific restaurant and use the edit/delete buttons.
