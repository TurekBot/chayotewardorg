# Chayote Ward Website
This page is accessible at chayoteward.org 

## Links
One main purpose of the project is to make easy-to-remember links.

### Adding new links
To add a new link, simply add it to the [`src/links.json`](src/links.json) file.

Once it's saved here on GitHub, the site will automatically re-build and re-deploy using GitHub Actions; see [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) for details

### Remembering the links
If anyone wants to see all the links they can visit, they can go to [chayoteward.org/links](http://chayoteward.org/links) to refresh they're memory.

## The `public` folder
In the future, if it makes sense to, you can add things to the `public` folder, and they'll automatically be added to the website. You might consider [setting up a Jekyll site](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll) to keep things simple.

## But How?
### The Link Shortener
This project uses a very simple link shortener package called [Suri](https://github.com/surishortlink/suri), specifically, we used the [GitHub Pages template](https://github.com/surishortlink/suri-deploy-github).

### The Domain Name (chayoteward.org)
Brother Bradley Turek bought chayoteward.org from namecheap.com. If he ever leaves, he can easily transfer this project and the domain name to whoever needs it.
