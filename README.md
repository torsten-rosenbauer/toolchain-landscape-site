# Toolchain Landscape for Embedded Automotive Software Development

This site is published via GitHub Pages and provides a visual landscape of tools and technologies for embedded automotive software development.

## Live Site

Access the landscape at: [https://torsten-rosenbauer.github.io/toolchain-landscape-site/](https://torsten-rosenbauer.github.io/toolchain-landscape-site/)

## About

This landscape is generated using [landscape2](https://github.com/cncf/landscape2) and is maintained in a separate source repository. This repository only contains the static site files for public access via GitHub Pages.

- **Deployed branch:** `gh-pages`

## How it works

- The source repository builds the landscape using landscape2 and pushes the output to the `gh-pages` branch of this repository.
- This repository is configured to serve the `gh-pages` branch via GitHub Pages.

## Updates

To update the landscape:
1. Make changes in the source repository.
2. The GitHub Actions workflow will automatically rebuild and deploy the updated site here.
