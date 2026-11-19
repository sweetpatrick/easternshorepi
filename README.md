# Eastern Shore Private Eye

A Christmas gift: a case-board app for the Eastern Shore's finest amateur sleuth, with a wisecracking partner named Dougie.

Live at https://easternshorepi.ca

- `index.html` is the whole app. Cases, people and connections are saved in the browser on each device (localStorage). Nothing about the people she tracks is stored in this repo or on any server.
- `sw.js` lets it work offline and install to the home screen. Bump `VERSION` in it whenever `index.html` changes.
- `manifest.webmanifest` and `icons/` give it an app name and icon when installed.
- `CNAME` points GitHub Pages at the custom domain.
