# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a static personal website for Bicky Bhullar, hosted via GitHub Pages at bickybhullar.com. The entire site is a single `index.html` file with inline CSS — no build tools, frameworks, or dependencies.

## Architecture

- **index.html** — The complete site: markup, styles (inline `<style>` block), and content. Uses flexbox layout with a max-width container. All CSS is in a single `<style>` element in `<head>`.
- **CNAME** — Custom domain configuration pointing to bickybhullar.com.
- **Static assets** — favicon.png and several SVG icons (linkedin.svg, mastodon.svg, instagram.svg, etc.) in the repo root. Not all SVGs are currently referenced by the HTML.

## Deployment

Pushing to the `master` branch automatically deploys via GitHub Pages. There is no build step — just edit `index.html` and push.
