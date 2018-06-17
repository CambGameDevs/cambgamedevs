# Cambridge Game Dev

A repertoire of events, meet ups, rules, helper docs and games of the cambridge game dev scene.

## Run

Make sure that you have the Gatsby CLI program installed:

```sh
npm install --global gatsby-cli

cd cambridgegamedev
npm install
```

Then you can run it by:

```sh
cd cambridgegamedev
gatsby develop
```

## Deploy

This project has netlify integrated - a build and deploy tool that works with gatsby and github repos.

Creating a pull request against `master` will:

* pre-merge: attempt to build & deploy to a preview bucket

* on-merge: if the above passes successfully, automatically build & deploy to live
