# Jekyll Template

Get up & running with a static site quickly.

## Steps

1. Set up a local folder for the site and install the template:
    ```sh
    $ mkdir domainname.here
    $ cd jekyll-template/
    $ ./install ../domainname.here
    $ cd ../domainname.here
    ```
1. Update `README.md` with an overview of your site.
1. Update `_config.yml` with your site values.
1. Update `CNAME` with your domain name.
1. Design a logo and use [Favicon Generator](http://www.favicon-generator.org/)
   to generate various size icons, putting them in `img/favicon/`.
1. Choose a color scheme with [Coolers.co](https://coolors.co/) and export as
   SCSS to `_sass/_palette.scss`.
1. Update `style/style.scss` with color values, etc.
1. Serve it up locally to tweak:
    ```sh
    $ bundle
    $ bundle exec jekyll serve --drafts
    ```
1. Add your first post in `_posts/`.
1. Push it to GitHub Pages: `git push -u origin master`.
1. Set up a Cloudflare site for the domain name, with:
  * CNAME `@` as an alias of `h3h.github.io`
  * CNAME `www` as an alias of `h3h.github.io`
  * Crypto/SSL set to `Full`
  * 1 Page Rule: `http://domainname.here/*` to Always Use HTTPS
  * Enable Development Mode while testing
1. Change domain DNS to `mary.ns.cloudflare.com` and `sam.ns.cloudflare.com`.
1. Update GitHub repository settings to set GitHub Pages source as `master`.
