# Glacieerr.github.io

My interactive homepage: **[glacieerr.github.io](https://glacieerr.github.io/)**

[![The interactive homepage: a lock screen with a clock for Albany, NY and the planets around my avatar](https://glacieerr.github.io/og-image.png)](https://glacieerr.github.io/)

One HTML file that makes no network requests when it opens: an app behind each planet, tonight's sky for 172 cities, time travel and ⌘K search.

## Where the code is

The page is built from my profile repository, [Glacieerr/Glacieerr](https://github.com/Glacieerr/Glacieerr), in its [`pages/`](https://github.com/Glacieerr/Glacieerr/tree/main/pages) folder. [How it works](https://github.com/Glacieerr/Glacieerr/blob/main/HOW-IT-WORKS.md) explains the whole thing.

This repository only builds and publishes it. [`.github/workflows/publish.yml`](.github/workflows/publish.yml) checks out the profile repository and runs the same checks as its own workflow: every stated fact, the clock and the sky at the edges of time, and every check of the page in headless Chrome. It publishes the page with GitHub Pages only when they all pass. It runs by hand, on every push here and every night; a nightly run stops early unless the profile repository has changed.

## License

The workflow and this README are under the [MIT license](LICENSE). The page itself is covered by the profile repository's license notes.
