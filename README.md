<h1 align="center">
  <img src="logo.png" alt="browser-b0X" width="160">
</h1>

**Free apps that run on your own computer.** This repository is the browser-b0X home page at
[browser-b0x.github.io](https://browser-b0x.github.io/): one page that lists the three apps and links to each one.

| App | What it does | Site | Source |
| --- | --- | --- | --- |
| Marteloio | An eBay listing generator: type your notes and get a title, item specifics and an HTML description to paste in | [Site](https://browser-b0x.github.io/marteloio/) | [Repository](https://github.com/browser-b0X/marteloio) |
| SuperBookmarks | A local bookmark manager for Windows: one library for browser bookmarks, Telegram and WhatsApp links and saved posts, with offline copies | [Site](https://browser-b0x.github.io/super-bookmark-manager/) | [Repository](https://github.com/browser-b0X/super-bookmark-manager) |
| Startclip | An offline start-command dashboard: one HTML page that maps the apps on your machine and copies the right start command | [Site](https://browser-b0x.github.io/startclip/) | [Repository](https://github.com/browser-b0X/startclip) |

## How it's built

The site is one HTML page with its styles and script inside it. It loads nothing from other sites until you press a
"Watch the tour" button, which then loads that app's video.

| Part | Built with |
| --- | --- |
| The page | One `index.html` with plain CSS and JavaScript, no framework and no build step |
| Fonts | Space Grotesk and Manrope, hosted here under the SIL Open Font License |
| Search | A `sitemap.xml` that lists this page and the three app sites, a `robots.txt` that points to it, and a canonical link |
| Hosting | GitHub Pages, from the `main` branch |

Much of this site's code was written with [Claude Code](https://claude.com/claude-code). browser-b0X designs the page,
decides what it says and how it looks, directs the build and checks each change in a browser. Claude is credited as a
co-author on the commits.

## License

The code is under the [MIT License](LICENSE). The browser-b0X name and logo, and each app's name and logo, are
trademarks of browser-b0X. The fonts keep their own licenses, which are in `fonts/`.
