# Pokémon Card — HTML/CSS Practice

A responsive Pokémon card component built in pure HTML and CSS, declined into three variants (Charmander, Squirtle, Bulbasaur) with a home page linking them together.

**[Live Demo →](https://aleksrdesign.github.io/pokemon-card/)**

## Overview

This project is a front-end practice exercise focused on building a clean, reusable card layout from scratch — no frameworks, no CSS libraries. Each variant reuses the same HTML/CSS structure with only content and accent colors changing, to practice writing maintainable, consistent styles.

## Tech Stack

- HTML5
- CSS3 (Flexbox, positioning, custom properties-free by design)
- Google Fonts (Roboto)

## Project Structure

```
├── index.html
├── style.css
├── variant01/ # Charmander (Fire)
│ ├── variant01.html
│ ├── variant01.css
│ └── images/
├── variant02/ # Squirtle (Water)
│ ├── variant02.html
│ ├── variant02.css
│ └── images/
└── variant03/ # Bulbasaur (Grass)
├── variant03.html
├── variant03.css
└── images/
```

## Concepts Practiced

- Box model and `box-sizing`
- Positioning (`relative`, `absolute`, `z-index`) for overlapping elements
- Flexbox for layout (card lists, stat rows)
- CSS filters (`drop-shadow`) vs. `box-shadow`
- Pseudo-classes (`:hover`) and transitions
- Consistent, content-based class naming

## Credits

Pokémon sprites provided by [PokeAPI Sprites](https://github.com/PokeAPI/sprites) — many thanks to the PokeAPI team for this free, well-organized resource.

Pokémon artwork, names, and related elements are property of Nintendo, Game Freak, and The Pokémon Company. This is a non-commercial learning project with no official affiliation to these companies.
