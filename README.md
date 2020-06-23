# bulma-cool-checkboxes

[![npm](https://badgen.net/npm/v/@cityssm/bulma-cool-checkboxes)](https://www.npmjs.com/package/@cityssm/bulma-cool-checkboxes)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/c9bd081b077d4add8ccff989eb02c5fb)](https://www.codacy.com/gh/cityssm/bulma-cool-checkboxes?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=cityssm/bulma-cool-checkboxes&amp;utm_campaign=Badge_Grade)

100% CSS based checkbox for <a href="http://bulma.io" target="_blank">Bulma.io</a>

Based on the work of Aslam Shah,
[hunzaboy/Cool-Checkboxes-for-Bulma.io](https://github.com/hunzaboy/Cool-Checkboxes-for-Bulma.io), with the following changes.

-   Converted from CSS to SCSS.
-   Using Bulma colour variables for easier customization.
-   Made to work with Font Awesome 5.
-   Removed the `styled` class as it's always used.
-   Removed the `is-circular` class.
-   Removed the `type="radio"` styles.

## How to use

`npm install @cityssm/bulma-cool-checkboxes`

To customize the colours in your SCSS,
import the bulma-cool-checkboxes.scss file **after** Bulma.

```scss
// Set your Bulma variables before importing.

@import 'bulma/bulma';
@import '@cityssm/bulma-cool-checkboxes/bulma-cool-checkboxes';
```

If no customization is necessary (i.e. vanilla Bulma), just use the CSS.

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bulma/0.8.2/css/bulma.min.css" />
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css" />
<link rel="stylesheet" href="bulma-radio-checkbox.min.css" />
```
