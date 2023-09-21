<a href="https://vianetz.github.io/spectre-css">
  <img src="https://vianetz.github.io/spectre-css/img/spectre-logo.svg" width="72" height="72" alt="spectre.css">
</a>

## Spectre.css (fork)

[![Reviewed by Hound](https://img.shields.io/badge/Reviewed_by-Hound-8E64B0.svg)](https://houndci.com)

Spectre.css is a lightweight, responsive and modern CSS framework.

- Lightweight (~10KB gzipped) starting point for your projects
- Flexbox-based, responsive and mobile-friendly layout
- Elegantly designed and developed elements and components

Spectre is a side project based on years of CSS development work on a large web service project. Spectre only includes modern base styles, responsive layout system, CSS components and utilities, and it can be modified for your project with Sass/Scss compiler.

## Purpose of this fork

As the original author unfortunately is [no longer responsive](https://github.com/picturepan2/spectre/issues/684) I started this fork of Spectre.css to continue development and update with latest browser versions.

My **main goal** for this fork is to keep the spirit of the excellent original work by the author, which means
- keep it extremely lightweight and simple
- stay up-to-date with latest browser developments

Of course I'm happy to accept pull requests for bugfix or feature proposals.

## Getting started

There are 4 ways to get started with Spectre CSS framework in your projects. You can either manually install or use NPM, Yarn and Bower.

### Install manually
Download the compiled and minified [Spectre CSS files](https://github.com/vianetz/spectre-css/releases) and include `spectre.min.css` in your website or web app `<head>` part:

`<link rel="stylesheet" href="spectre.min.css">`

### Install with NPM
`$ npm install --save https://github.com/vianetz/spectre-css`

### Install with Yarn
`$ yarn add npm install --save https://github.com/vianetz/spectre-css`

### Install with Bower
`$ bower install npm install --save https://github.com/vianetz/spectre-css --save`

## Compiling custom version

You can compile your custom version of Spectre.css. Read [the documentation](https://vianetz.github.io/spectre-css/getting-started/custom.html).

## Documentation and examples

### Elements

- [Typography](https://vianetz.github.io/spectre-css/elements/typography.html)
- [Tables](https://vianetz.github.io/spectre-css/elements/tables.html)
- [Buttons](https://vianetz.github.io/spectre-css/elements/buttons.html)
- [Forms](https://vianetz.github.io/spectre-css/elements/forms.html)
- [Icons.css](https://vianetz.github.io/icons.css) - CSS ONLY
- [Labels](https://vianetz.github.io/spectre-css/elements/labels.html)
- [Code](https://vianetz.github.io/spectre-css/elements/code.html)
- [Media](https://vianetz.github.io/spectre-css/elements/media.html)

### Layout
- [Flexbox grid](https://vianetz.github.io/spectre-css/layout/grid.html) 
- [Responsive](https://vianetz.github.io/spectre-css/layout/responsive.html)
- [Hero](https://vianetz.github.io/spectre-css/layout/hero.html)
- [Navbar](https://vianetz.github.io/spectre-css/layout/navbar.html)

### Components
- [Accordions](https://vianetz.github.io/spectre-css/components/accordions.html)
- [Avatars](https://vianetz.github.io/spectre-css/components/avatars.html)
- [Badges](https://vianetz.github.io/spectre-css/components/badges.html)
- [Breadcrumbs](https://vianetz.github.io/spectre-css/components/breadcrumbs.html)
- [Bars](https://vianetz.github.io/spectre-css/components/bars.html)
- [Cards](https://vianetz.github.io/spectre-css/components/cards.html)
- [Chips](https://vianetz.github.io/spectre-css/components/chips.html)
- [Empty states](https://vianetz.github.io/spectre-css/components/empty.html)
- [Menu](https://vianetz.github.io/spectre-css/components/menu.html)
- [Nav](https://vianetz.github.io/spectre-css/components/nav.html)
- [Modals](https://vianetz.github.io/spectre-css/components/modals.html)
- [Pagination](https://vianetz.github.io/spectre-css/components/pagination.html)
- [Panels](https://vianetz.github.io/spectre-css/components/panels.html)
- [Popovers](https://vianetz.github.io/spectre-css/components/popovers.html)
- [Steps](https://vianetz.github.io/spectre-css/components/steps.html)
- [Tabs](https://vianetz.github.io/spectre-css/components/tabs.html)
- [Tiles](https://vianetz.github.io/spectre-css/components/tiles.html)
- [Toasts](https://vianetz.github.io/spectre-css/components/toasts.html)
- [Tooltips](https://vianetz.github.io/spectre-css/components/tooltips.html)

### Utilities

- [Utilities](https://vianetz.github.io/spectre-css/utilities.html) - colors, display, divider, loading, position, shapes and text utilities

### Experimentals
- [360-Degree Viewer](https://vianetz.github.io/spectre-css/experimentals/viewer-360.html) - CSS ONLY
- [Autocomplete](https://vianetz.github.io/spectre-css/experimentals/autocomplete.html)
- [Calendars](https://vianetz.github.io/spectre-css/experimentals/calendars.html)
- [Carousels](https://vianetz.github.io/spectre-css/experimentals/carousels.html) - CSS ONLY
- [Comparison Sliders](https://vianetz.github.io/spectre-css/experimentals/comparison.html) - CSS ONLY
- [Filters](https://vianetz.github.io/spectre-css/experimentals/filters.html) - CSS ONLY
- [Meters](https://vianetz.github.io/spectre-css/experimentals/meters.html)
- [Off-canvas](https://vianetz.github.io/spectre-css/experimentals/off-canvas.html) - CSS ONLY
- [Parallax](https://vianetz.github.io/spectre-css/experimentals/parallax.html) - CSS ONLY
- [Progress](https://vianetz.github.io/spectre-css/experimentals/progress.html)
- [Sliders](https://vianetz.github.io/spectre-css/experimentals/sliders.html)
- [Timelines](https://vianetz.github.io/spectre-css/experimentals/timelines.html)

## Browser support
Spectre uses [Autoprefixer](https://github.com/postcss/autoprefixer) to make most styles compatible with earlier browsers and [Normalize.css](https://necolas.github.io/normalize.css/) for CSS resets. Spectre is designed for modern browsers. For best compatibility, these browsers are recommended:

- Chrome (LAST 4)
- Microsoft Edge (LAST 4)
- Firefox (EXTENDED SUPPORT RELEASE)
- Safari (LAST 4)
- Opera (LAST 4)
- Internet Explorer 10+

Spectre supports Internet Explorer 10+, but some HTML5 and CSS3 features are not perfectly supported by Internet Explorer.

Designed and built with ♥ by [Yan Zhu](https://twitter.com/picturepan2). Feel free to submit a pull request. Help is always appreciated.
