# Deep playground

Deep playground is an interactive visualization of neural networks, written in typescript using d3.js.
We use github issues for tracking new requests and bugs. Your feedback is highly appreciated!

**If you'd like to contribute, be sure to review the [contribution
guidelines](CONTRIBUTING).**

## Development

Running the visualization locally needs to serve all the files from the `dist` directory. Run `npm install`, then `npm run serve` if you don't have one handy. To see the visualization, visit `http://localhost:8080/` on browser.

When developing, use `npm run serve-watch`. This starts a static server and watchers to automatically compile the typescript, html and css files whenever they change.

To produce a minified javascript file for production, run `npm run build`.

To push to production: `git subtree push --prefix dist origin gh-pages`.

This is not an official Google product.
