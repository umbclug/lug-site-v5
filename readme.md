# UMBC Linux Users Group

Welcome to the current iteration of our club's website!

## Contributing

This website is meant to be primarily updated and maintained by officers and system administrators. That said, community contributions are more than welcome. Here's what you need to know.

### Directories

- **/content** - Where all the markdown files live. This is where the page content is written.
- **/content/blog** - This contains the pages found under the 'posts' tab. This is currently a work in progress. But there is where presentations and other announcements should go.
- **/static** - Contains all media (presentations & images).
- **/hugo.toml** - The primary config file. Defines things like the global header and footer.

## Things to do

- Setup an RSS feed
- Sorting blog posts by tag; (e.g. Presentation, Announcement.. etc)
- Fix the favicon
- Add a license to the git repo

## Stack

We are currently using Hugo as a static site generator. At its core this takes a bunch of markdown files and it turns it into a presentable website.

- **Webserver:** Nginx
- **SSG:** [Hugo](https://github.com/gohugoio/hugo)
- **Theme:** [Hextra](https://github.com/imfing/hextra)

There is a github action that will trigger the website to update on our webserver host when a push is made to the repository.
