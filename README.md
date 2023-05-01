[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Deploy to GitHub Pages](https://github.com/vascoguita/vasco.guita.org/actions/workflows/deploy.yml/badge.svg)](https://github.com/vascoguita/vasco.guita.org/actions/workflows/deploy.yml)

# Vasco Guita :rocket:

Vasco Guita's personal website - https://vasco.guita.org.

The project was generated from [CaiJimmy/hugo-theme-stack-starter](https://github.com/CaiJimmy/hugo-theme-stack-starter), a template for building websites with [Hugo Theme Stack](https://stack.jimmycai.com/).

## Build :hammer:

Before building the website, make sure to have [Go](https://go.dev/doc/install) and [Hugo](https://gohugo.io/installation) (the extended edition) installed.

To build the website:
1. Clone the project
```
git clone https://github.com/vascoguita/vasco.guita.org.git
```
2. Go to the project directory
```
cd vasco.guita.org
```
3. Build the website
```
hugo --gc --minify
```
4. Serve the website
```
hugo server
```

To view the website, open the URL displayed in your terminal.

## Deployment :satellite:

The website is deployed to [GitHub Pages](https://pages.github.com/) with the [GitHub Actions](https://github.com/features/actions) workflow defined in `.github/workflows/deploy.yml`.

The workflow builds and deploys the website whenever a change is pushed to the `master` branch.


## Feedback :mailbox:

If you have any feedback, please send it to vasco@guita.org.

