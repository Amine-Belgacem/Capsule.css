# Capsule.css

Capsule.css is a lightweight, minimal CSS framework for building clean, responsive, and reliable web interfaces without the overhead of larger UI libraries.

It is designed for developers who want a small but dependable foundation for websites, prototypes, and simple production projects. Capsule.css focuses on three core principles:

- **Encapsulation**: it remains self-contained and can be used alongside other frameworks without causing conflicts.
- **Self-reliance**: it includes the essentials needed to build usable layouts and components right away.
- **Minimalism**: it stays lightweight, simple, and easy to work with.

## Why choose Capsule.css?

Capsule.css is a practical choice when you want:

- a lightweight alternative to heavier front-end frameworks
- a simple responsive grid system
- ready-to-use layout helpers and basic component styling
- a clean starting point for small to medium web projects

It is not meant to replace every feature of large frameworks, but to provide a solid and efficient foundation for fast UI development.

## Features

- Small footprint
- Responsive layout helpers
- Mobile-first grid behavior
- Basic styled HTML elements
- Minimal setup and low complexity

## Quick start

Include the stylesheet in your project:

```html
<link rel="stylesheet" href="./dist/capsule.min.b0.2.css" />
```

Then build a layout using the Capsule structure:

```html
<div class="capsule">
  <div class="row gap:8 padding:5 adapt-medium:switch">
    <div class="box:6">
      <img class="width:max" src="./demo/img/youtube_tutorial.svg" alt="Example" />
    </div>
    <div class="col:9 gap:2 align:middle">
      <h5>Build fast with Capsule</h5>
      <p>A lightweight foundation for modern, responsive interfaces.</p>
      <a href="#" class="button width:third adapt-medium:stretch">Learn more</a>
    </div>
  </div>
</div>
```

## Demo

A demo page is included in the repository:

- [demo/index.html](demo/index.html)

Open it locally to see the framework in action.

## Project structure

- [dist/](dist/) — built CSS files
- [demo/](demo/) — example page and assets
- [package.json](package.json) — package metadata

## License

This project is licensed under the MIT License.
