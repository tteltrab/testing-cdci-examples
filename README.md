# testing-cdci-examples

A set of examples and slides for an intro in to CD/CI with Node.

The slides for this repo are powered by [Armadillo](https://github.com/Snugug/gulp-armadillo).

## Deploying to GitHub Pages

Almost everything is set up for your Armadillo to deploy your site to [GitHub Pages](https://pages.github.com/). You need to create an [personal access token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/) with the [`repo`](https://developer.github.com/v3/oauth/#scopes) scope. Keep this a secret! It's what lets Armadillo write to your `gh-pages` branch and deploy for you! Once you've got your token, in your [Travis CI environment variables](https://docs.travis-ci.com/user/environment-variables/#Defining-Variables-in-Repository-Settings), add a `GH_TOKEN` variable and set it to your token. Be sure to enable your GitHub repo from Travis CI!

