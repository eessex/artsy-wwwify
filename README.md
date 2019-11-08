# artsy-wwwify
A tiny app that 301 redirects requests to www.artsy.net

### Meta
* State: production
* Production: https://artsy.net
* Staging: N/A
* GitHub: https://github.com/artsy/artsy-wwwify
* CI: [CircleCI](https://circleci.com/gh/artsy/artsy-wwwify); merged PRs to `master` are automatically built and deployed to staging. [Make a pull request from `staging` to `release`](https://github.com/artsy/artsy-wwwify/compare/release...staging?expand=1) to trigger a release to production.
Point People: @joeyAghion

### Development

    npm install
    npm start

or in docker:

    hokusai dev start

### Testing

    npm install
    jest

or in docker:

    hokusai test

