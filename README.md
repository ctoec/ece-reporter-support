# ECE Reporter Help
 A collection of help guides for the ECE Reporter application.

 ## Local Setup
1. Install and configure [Jekyll and all its prerequisites](https://jekyllrb.com/docs/installation/).

1. Assuming Ruby and Bundler have been installed successfully, update Bundler.
    ```
    gem install bundler
    ```

1. From project root, install all Ruby dependencies.
    ```
    bundle install
    ```

1. Start up the application!
    ```
    bundle exec jekyll serve
    ```

## Deploy
Deployments and hosting are both managed by [GitHub Pages](https://github.com/ctoec/ece-reporter-support/settings/pages), currently triggered on each and every merge into our `base` branch.