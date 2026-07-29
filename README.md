# Sticky Wall

A simple **Sticky Wall / To-Do List** web app built with HTML and CSS.
This project is mainly a learning exercise to practice front-end fundamentals (layout, styling, structure), and it may grow into something bigger in the future.

## Preview

The app displays a menu (sidebar with lists and tags) and a main sticky-notes wall where each note represents a to-do list/card.

## Features

- Collapsible sidebar menu that expands on hover, showing lists with color-coded icons and item counters
- Tags section with colored tag buttons and an "Add New Tag" action
- Sticky notes wall with two note color variants (green / orange)
- Scrollable notes area: the sidebar and page title stay fixed while the notes container scrolls independently once it overflows
- "Add new sticky" button to (visually) add new notes
- Custom favicon and [Font Awesome](https://fontawesome.com/) icons throughout the UI

## File Structure

```
to-do list v2/
│
├── index.html               # Main HTML file (currently contains everything)
└── assets/
    ├── css/
    │   └── style.css        # Main stylesheet
    └── img/
        └── icon.png         # Favicon
```

## Color Palette

| Color          | Hex       | Usage                               |
| -------------- | --------- | ----------------------------------- |
| App Background | `#222531` | Page background                     |
| Panel Navy     | `#323645` | Sidebar / add-new-sticky background |
| Chip Navy      | `#232633` | Chip / badge background             |
| Light Green    | `#B6F36B` | Sticky note (green variant) & tags  |
| Orange         | `#FF9B61` | Sticky note (orange variant) & tags |
| White          | `#FFFFFF` | Primary text                        |
| Muted Gray     | `#9096A8` | Secondary/muted text, hover states  |

> Colors are defined as CSS custom properties (`:root` variables) in `style.css` for easy reuse and theming.

## Pages

Currently, the project is a single-page app:

- `index.html` — contains the full structure (menu, lists, tags, and the sticky notes wall).

## Technologies Used

- **HTML5** — page structure and markup
- **CSS3** — styling, layout (Flexbox), custom properties, hover transitions, and responsiveness
- **[Font Awesome](https://fontawesome.com/)** — icon set (via CDN)

## Setup

1. Clone the repository
2. Open `index.html` in any web browser
3. No build process or dependencies required

## License

This project is for educational purposes only.
