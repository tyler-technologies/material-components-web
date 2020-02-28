<!--docs:
title: "Scaffold"
layout: detail
section: components
excerpt: "A CSS only scaffold layout."
iconId: responsive_layout
path: /catalog/scaffold/
-->

# Scaffold
Material design’s responsive UI is based on a column-variate grid layout. It has 12 columns on desktop, 8 columns on tablet and 4 columns on phone.

## Installation

```
npm install @tyler-material/scaffold
```

## Usage

### HTML Structure

```html
<template>
  <div class="mdc-scaffold">
    <div class="mdc-scaffold__header"></div>
    <div class="mdc-scaffold__body">
      <div class="mdc-scaffold__body-left"></div>
      <div class="mdc-scaffold__body-header"></div>
      <div class="mdc-scaffold__body"></div> 
      <div class="mdc-scaffold__body-footer"></div>
      <div class="mdc-scaffold__body-right"></div>
    </div>
    <div class="mdc-scaffold__footer"></div>
  </div>
</template>
```

### Styles

```scss
@import "@tyler-material/scaffold/mdc-scaffold";
