
# wallpaper-scrapper
A cli app for searching for (preferably) lax licensed wallpapers.

Scrappy can currently scrape unsplash.com, wallhaven.cc, photocollections.io & magdeleine.co

Want a site added ? Create an issue with a request and i'll see what i can do. Feel free to contibute your own pull requests are welcome.

## Install
Ensure you have either w3m or feh installed.

*Note if you are using w3m you will also need imagemagick installed

Clone the repository:

```
git clone https://github.com/ashwinsingh2007/wallpaper-scrapper.git
```

Install dependencies:

```
npm install
```

Run or create a bash/zsh alias too the bin/scrappy executable.

## Config file
Scrappy comes with a config file with some default options.
w3m does not support inline image viewing on all terminal emulators if w3m doesn't work with your terminal change w3m out for feh.

You can also set up some folders to save images too and it will prompt you to select the folder upon saving. An example is provided on how to do this.
