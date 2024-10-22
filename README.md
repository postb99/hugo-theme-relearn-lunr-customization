# hugo-theme-relearn-lunr-customization
Customized [Lunr search experience](https://lunrjs.com/) within a site using [Hugo Relearn theme](https://mcshelby.github.io/hugo-theme-relearn/).

## Why

On [my poetry web site](https://poesieland.github.io/), I'd like to customize javascript code allowing to integrate Lunr library. However, this is not practical testing on a live website with a 30-second build time because this is how the Hugo Relearn theme works, it feeds Lunr index at build time.

Lunr is a very nice search engine but the initial authors of the theme have made some decisions and I'd like to override either general cases (multi-word exact search, enable wildcard search) or specific cases (French œ digraph).

Initial issue: https://github.com/poesieland/poesieland.github.io/issues/48

## What

A very simple site using Hugo Relearn theme and few content tailoring my search test cases. 

## How

For now I copy and [override the search.html partial](https://mcshelby.github.io/hugo-theme-relearn/configuration/sitemanagement/structure/index.html) to use another javascript file, because Lunr documentation has examples but it's totally unclear how to properly include [proposed customizations](https://lunrjs.com/guides/customising.html). I've made some tries and feel it's easier to hack and comment readable code the theme provides.


