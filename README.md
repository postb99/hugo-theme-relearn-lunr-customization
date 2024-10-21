# hugo-theme-relearn-lunr-customization
Customized Lunr search experience within a site using Hugo Relearn theme

## Why

On my poetry web site, I'd like to customize javascript code allowing to use Lunr library. However, this is not practical testing on a live website with a 30-second build time because this is how the Hugo Relearn theme works, it feeds Lunr index at build time.

Lunr is a very nice search engine but the initial authors of the theme have made some decisions and I'd like to override either general cases (multi-word exact search, enable wildcard search) or specific cases (French œ digraph).

Initial issue: https://github.com/poesieland/poesieland.github.io/issues/48

## What

A very simple site using Hugo Relearn theme and few content tailoring my search test cases. 

## How

I guess I can define my own page archetype or use custom partials.

https://mcshelby.github.io/hugo-theme-relearn/configuration/customization/designs/index.html
