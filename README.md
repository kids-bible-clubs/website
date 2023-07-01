# Kids Bible Clubs via Hugo

Hugo is a Static Site generator. There is lots of magic behind the scenes.

## Development

**Requirements**

- [hugo](https://gohugo.io/installation/) (I'm using an older version [v0.88.1](https://github.com/gohugoio/hugo/releases/tag/v0.88.1))

Start the site locally by running `hugo server` in a terminal. Instructions on the screen should tell you how to access the site.

### How to update site data

To make changes to the content, modify only the files in [content](content).

### Template and layout

The theme is a slightly modified version of (bigspring-light)[https://github.com/gethugothemes/bigspring-light]. The theme has been renamed to [kids-bible-clubs-website](themes/kids-bible-clubs-website).

## Production Build

Run the `hugo` command to create or update the [public](public) directory. When `public` gets pushed to master, a github action will automatically update the site.