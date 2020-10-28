<p>
  <a href="https://github.com/luciandavila/serverless-chat/actions?query=workflow%3Aci"><img alt="Serverless Chat ci status" src="https://github.com/luciandavila/serverless-chat/workflows/ci/badge.svg"></a>
</p>

# serverless-chat

🚧 **This project is still under construction and might not work perfectly!** 🚧

Simple serverless chat app created with Nuxt.js, connected to google cloud tools like Firebase Authentication and Firebase Realtime Database.

<!-- The app can be accessed through the static hosting service Firebase Hosting, at <a href="https://serverless-chat-a3350.web.app/">https://serverless-chat-a3350.web.app/</a>, and can be installed as a PWA. -->

This project was coded as an experiment, during my free time 😋

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

## Linting and Testing

```bash

# running js linter
$ yarn lint:js

# running styles linter 
$ yarn lint:style

# running all linters
$ yarn lint

# running tests
$ yarn test
```

## Deployment

```bash
# install firebase cli and login
$ curl -sL https://firebase.tools | bash
$ firebase login

# generate and deploy code to firebase hosting service
$ yarn generate
$ firebase deploy
```

## Bugs and Contribution

For bugs and feature suggestions open an issue on Github. For code contributions fork the repo, make your changes and create a pull request.

If you want to contribute but do not know where to start, improvements on error handling, test coverage and usability are top priority.
