## Getting started

This grid module gives you the ability to build a responsive site. It uses the default media query settings, found in 'Settings'. Define the settings for your site grid here. Some of these settings may not work, as they're deprecated since and older version of Precursor.

## Settings (important)
  - isResponsive: Disabled all responsive break-points in the grid
  - mobileOverride: Depricated
  - tabletResponsive: Removes all tablet responsive break-points
  - desktopResponsive: Removes all desktop responsive break-points

## Markup

### Wrapping
Add these two containers to your markup, otherwise the grid won't work. You can add as many elements after these wrappers as you like, just don't forget them.

```html
    &lt;div class=&quot;precursor&quot;&gt;
        &lt;div class=&quot;col-container&quot;&gt;
            Rows go in here
        &lt;/div&gt;
    &lt;/div&gt;
```

### Rows
Anytime you need a set of columns, they require wrapping inside a 'row'. The row markup clears any floating columns inside them. Like most other grid based CSS frameworks, columns must add up to '12'.

```html
    &lt;div class=&quot;row&quot;&gt;
        Columns go in here
    &lt;/div&gt;
```

### Columns
Columns require two classes in order to work. The 'col' class add all of the floating properties, while the 'col-n' class adjusts the width. You can combine blocks of different sizes into your rows, as long as they add up to 12. The larger the number in 'col-n', the wider the column.

```html
    &lt;div class=&quot;col col-6&quot;&gt;
      Content goes in here
    &lt;/div&gt;
    &lt;div class=&quot;col col-6&quot;&gt;
      Content goes in here
    &lt;/div&gt;
```

## Files
  - Grid.less: Edit this file
  - Grid.css: Compiled version of this module