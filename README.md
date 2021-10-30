# reveal.js-template

A template to generate [reveal.js](https://revealjs.com/) markdown presentation repositories with reaveal.js as submodule.

This template uses reveal.js version 4.1.2 (see [reveal.js(github)](https://github.com/hakimel/reveal.js) for latest reveal tag).

## Demo

have a look a the according demo github pages for this repo: <https://litec-lectures.github.io/reveal.js-template/>

## Setup

1. Create a new github repo which uses this template.
2. Activate github pages within this repository (see `Settings -> Pages`) - most of the time using the main branch is ok.
3. If you clone the repo locally:
   1. Get the submodule files with `git submodule update --init --recursive`.
   2. For testing purposes run a local server for example with `vscode` and `live server` plugin.
4. Add own markdown files (sadly without yaml header!) and adapt `index.html` accordingly.
5. Upload (commit/push) changes to github.

For a detailed explanation see [pachanero-revealjs-template](https://github.com/pacharanero/create-new-revealjs-template).

## Sources

- [reveal.js](https://revealjs.com/)
- [reveal.js(github)](https://github.com/hakimel/reveal.js)
- [how to host reveal.js on github-pages](https://martinomensio.medium.com/how-to-host-reveal-js-slides-on-github-pages-and-have-a-tidy-repository-1a363944c38d)
- [pacharanero-revealjs-template](https://github.com/pacharanero/create-new-revealjs-template)
