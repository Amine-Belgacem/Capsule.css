# Capsule.css

Capsule.css is a lightweight, minimal CSS framework designed to help you build clean, responsive, and reliable web interfaces without the overhead of larger UI libraries.

It is built around three core ideas:

- **Encapsulation** — it stays self-contained and can be used alongside other frameworks without conflicting badly.
- **Self-reliance** — it includes the essentials needed to build usable layouts and components out of the box.
- **Minimalism** — it stays small, simple, and easy to understand.

## What Capsule is intended for

Capsule.css is intended for developers who want:

- a lightweight alternative to heavy front-end frameworks
- a simple responsive grid system
- ready-to-use utility-style helpers and basic component styling
- a clean starting point for small to medium web projects

It is not meant to replace every feature of large frameworks, but to provide a practical foundation for fast and consistent UI development.

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

Then create a layout using the Capsule structure:

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

You can open it locally to see the framework in action.

## Project structure

- [dist/](dist/) — built CSS files
- [demo/](demo/) — example page and assets
- [package.json](package.json) — package metadata

## Learn more

For more examples and deeper documentation, visit the project wiki:

- https://github.com/Amine-Belkacem/Capsule.css/wiki

## License

This project is licensed under the MIT License.
