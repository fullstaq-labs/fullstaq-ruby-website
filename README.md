# Fullstaq Ruby website

> For overarching Fullstaq Ruby issues, documents and other resources, or for other Fullstaq Ruby projects, please refer to the [fullstaq-ruby-umbrella](https://github.com/fullstaq-labs/fullstaq-ruby-umbrella) repo.

This repository contains [the Fullstaq Ruby website](https://fullstaqruby.org). It is a static site, built with [Middleman](https://middlemanapp.com/).

## Development

Middleman requires Ruby and Node.js, so install those first.

Before developing, install the gem bundle and the Node.js packages:

    bundle install
    yarn install --frozen-lockfile

Then spawn the Middleman server:

    bundle exec middleman s

Now the website will be accessible at http://127.0.0.1:4567.

## Publication

To publish the website, run:

    bundle exec rake build upload
