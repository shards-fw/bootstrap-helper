# bootstrap-helper
SCSS tools to generate CSS variables

NOTE: you need to set SASS_PATH="node_modules" or other way to ensure that sass search for modules in node_modules.

See file test-color.scss as an example how to use this package:



```
@import "bootstrap/scss/functions";
@import "bootstrap/scss/variables";
@import "bootstrap/scss/maps";
@import "bootstrap/scss/mixins";
@import "scss/mixins";


// Place your bootstrap changes here

// :end

@import "scss/bootstrap-helper";
```