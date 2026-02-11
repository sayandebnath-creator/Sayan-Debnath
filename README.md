# Shopify Hiring Test – Custom Page Implementation

## Overview
This project implements a custom Shopify page based on the provided Figma prototype.  
The page was built on top of the Dawn theme while strictly creating new sections from scratch as required.

## Features

- ✅ Custom **Banner Section**
  - Layered SVG background illustrations
  - Precise positioning and clipping
  - Jost font integration
  - Responsive layout
  - Editable content via Shopify Customizer

- ✅ Custom **Product Grid Section**
  - Up to 6 selectable products
  - Dynamic product rendering using Liquid
  - Structured for popup interaction
  - Clean, maintainable section schema

- ✅ Technical Requirements
  - No reuse of existing Dawn sections
  - Vanilla JavaScript only (no jQuery)
  - Clean, structured, and commented code
  - Responsive across desktop and mobile

## Tech Stack

- Shopify Liquid
- HTML5 / CSS3
- Vanilla JavaScript
- Dawn Theme (base)
- GitHub Integration for version control

## Structure
```bash
/sections
├── banner-custom.liquid
├── product-grid.liquid

/assets
├── custom.css.liquid
├── popup.js

/templates
├── page.test.json
```

## Notes

- SVG backgrounds are handled using layered CSS backgrounds.
- Fonts are loaded via Google Fonts (Jost).
- Code follows separation of concerns between structure, styling, and logic.

---

**Author:** Sayan Debnath
