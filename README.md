# UI Engineer Pairing Task

To get a feel for how you build UI, we'd like to you approach 3 separate problems which demonstrate your understanding of design, HTML, CSS, accessibility, componentisation and JavaScript. This project uses Vue.js (scaffolded with vue-cli), but feel free to use React if that's more comfortable for you.

It's important to note that the wireframes and design suggestions are just that. Part of being a great UI Engineer is your "feel" for UI and system design as a whole, so you're free to implement or suggest changes that you feel creates a better experience.

Don't worry if you don't have time to code each one, but please describe your thought process on how you'd tackle each one as if it were production-ready.

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

---

## Tasks

### 1. Responsive header with navigation

We'd like you to create a typical responsive header and navigation menu.

See [task-1-wireframe-design.png](/task-1-wireframe-design.png) for a suggested design approach.

#### Requirements:

* On narrow screens, the header will consist of a logo and hamburger menu button.
* Upon pressing the hamburger, the navigation menu will open, which lists the various options.
* On wider screens, the menu options are visible by default and right-aligned within the width-constrained header.
* When a user has shown intent to activate a particular item, it should be indicated as such.
* Use the provided SVGs in `/public/images` for the logos and icons.

The menu options are:

* Dashboard
* Search
* Bookings
* Job Board
* How to Guide

### 2. Trump's top tweets

We'd like you to display 11 of Trump's top tweets in a 4x3 column layout.

See [task-2-wireframe-design.png](/task-2-wireframe-design.png) for a suggested design approach.

#### Requirements:

* 11 tweets do not fit neatly in to 12 spaces, so make the first tweet sit in the middle of the layout, and be 2 columns wide.
* Make this first tweet bigger and bolder.
* Add a "zoom" interaction when the user has shown intent to activate a particular item.
* Responsive behaviour for smaller screens is outside the scope.

The tweet content is available at [tweets.md](/tweets.md).

### 3. "How we can help"

We'd like you to a list of 8 ways Hireup can people seeking support and translate them in to a striking, responsive layout.

See [task-3-wireframe-design.png](/task-3-wireframe-design.png) for a suggested design approach.

#### Requirements:

* Each item has a 32px gutter around it
* On narrow screens, the items are stacked vertically, and no "decorative" images are displayed.
* At an appropriate breakpoint, the the items are displayed in a disjointed grid-like pattern, with the maximum total width of the cells being 1140px.
* The images must not appear squashed at any time.
* The responsive behaviour between narrow and wide screens is up to your discretion.
* Use the provided placeholder image in `/public/images`.

The item content is available at [how-we-can-help.md](/how-we-can-help.md)

