<!--docs:
title: "Media"
layout: detail
section: components
excerpt: "Provides commonly-used media sizes."
iconId: phone
path: /catalog/media/
-->

# Media

MDC Media provides commonly-used media sizes.

## Installation

```
npm install @tyler-forge/media
```

## Usage

### Styles

```scss
@import "@material/media/mdc-media";
```

### Sass Mixins

Mixin | Description
--- | ---
`mdc-media-min($size)` | Generates min-width CSS for a element on certain device type
`mdc-media-max($size)` | Generates max-width CSS for a element on certain device type


#### `mdc-media-min($size)`

Generates min-width CSS for a element on certain device type. The mixin takes one parameter:

- `$size`: the target platform: `desktop-large`, `desktop`, `tablet-landscape`, `tablet-portrait` or `phone`.

#### `mdc-media-max($size)`

Generates max-width CSS for a element on certain device type. The mixin takes one parameter:

- `$size`: the target platform: `desktop-large`, `desktop`, `tablet-landscape`, `tablet-portrait` or `phone`.

### Sass Variables

Variables | Description
--- | ---
`mdc-media-breakpoints` | A SASS Map specifies the breakpoints width
