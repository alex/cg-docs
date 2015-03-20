## 18F CF Docs [![wercker status](https://app.wercker.com/status/b53005d7e69162205a5c9b63f3d65029/s/master "wercker status")](https://app.wercker.com/project/bykey/b53005d7e69162205a5c9b63f3d65029)

This repository contains the site code for the
18f Cloud Foundry documentation site.

### Running the site locally

This project uses [Hugo](https://gohugo.io) to build the site.

Once hugo is installed just run `hugo server -w` and browse to [http://localhost:1313](http://localhost:1313).

### Contributing

Hugo uses markdown to build the pages. Just add your page to the section you want inside the
content folder.

To validate links, run `bundle && bundle exec rake`. Requires Ruby 1.9+.

### Acknowledgement

The theme for the site has been "forked" from the [Hugo documentation site](https://gohugo.io/docs).
