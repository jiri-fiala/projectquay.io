# ProjectQuay.io

This repo contains the sources for the [ProjectQuay.io](https://www.projectquay.io/).

## Development

**Note** [`Node.js` is a required dependency](http://stackoverflow.com/a/6283074/6758654) on Linux machines

Firstly install the necessary packages on your machine:

    bundle install

To develop on your local machine run the middleman server and you
should be able to preview your changes at http://localhost:4567

    bundle exec middleman server

## Deployment

To deploy your changes please submit a pull request while following [our contribution guidelines](./CONTRIBUTING.MD)

Make sure to populate the `OPENSHIFT_GITHUB_ID` and `OPENSHIFT_GITHUB_SECRET` env variables to ensure authenticated GitHub API usage (and prevent request throttling).

## Staging Site for reviewing 

While the site is under development, you can review it here: https://staging-url-projectquay-io.apps.openshift-web.p0s5.p1.openshiftapps.com/ 
