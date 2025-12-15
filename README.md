## Contents

- [Usage](#usage)
- [Options](#options)
  - [Sidebar menu](#sidebar-menu)
  - [Themes](#themes)
  - [Reverse layout](#reverse-layout)
- [Development](#development)
- [Author](#author)
- [License](#license)


## Usage

View the GitHub for this template: [Lanyon](https://github.com/poole/lanyon).


### Sidebar menu

Create a list of nav links in the sidebar by assigning each page the correct layout in the page's [front-matter](http://jekyllrb.com/docs/frontmatter/).

```
---
layout: page
title: About
---
```


### Themes

Adjust the theme via `<body>` in `default.html`:

```html
<body class="theme-base-08">
  ...
</body>
```
Adjust the theme colours via theme hex codes in `public/css/lanyon.css`:

```
```


### Layout changes

Reverse the page orientation via:

```html
<body class="layout-reverse">
  ...
</body>
```

Make the sidebar overlap the viewport content via:

```html
<body class="sidebar-overlay">
  ...
</body>
```

This will keep the content stationary and slide in the sidebar over the side content. It also adds a `box-shadow` based outline to the toggle for contrast against backgrounds, as well as a `box-shadow` on the sidebar for depth.

It's also available for a reversed layout when you add both classes:

```html
<body class="layout-reverse sidebar-overlay">
  ...
</body>
```

Show an open sidebar on page load by modifying the `<input>` tag within the `sidebar.html` layout to add the `checked` boolean attribute:

```html
<input type="checkbox" class="sidebar-checkbox" id="sidebar-checkbox" checked>
```

## Author

**Mark Otto**
- <https://github.com/mdo>
- <https://twitter.com/mdo>


## License

Open sourced under the [MIT license](LICENSE.md).

<3
