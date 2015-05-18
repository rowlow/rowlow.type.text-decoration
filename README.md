# rowlow.type.text-decoration

A text util to take control over text decorations via CSS selectors

## Install

```
    bower install --save rowlow.type.text-decoration
```

## Variables

```
    $rowlow-text-decoration-namespace // Specific module namespace
```


## Usage

### Setup
```
    /* Set modules namespace (optional) */
    $rowlow-text-decoration-namespace: "namespace-";

    @import "bower_components/rowlow.type.text-decoration/main.scss"
```


### HTML
```
    <h1 class="text-decoration--underline"></h1>
    <h1 class="text-decoration--overline"></h1>
    <h1 class="text-decoration--line-through"></h1>
    <h1 class="text-decoration--none"></h1>
```

