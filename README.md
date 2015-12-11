# riot-animation-context riot tag (animation-context)

[![Build Status](https://travis-ci.org/any-code/riot-animation-context.svg?branch=master)](https://travis-ci.org/any-code/riot-animation-context)

> Riot JS Tag animation context for dealing with css transitions and animated addition and removal of riot tags

## Getting Started

### 1. Installation

``` bash
npm install riot-animation-context
```

### 2. Examples

``` javascript
   
   require('riot-animation-context')
   
```

``` html

<animation-context
    animate-on-mount="true" 
    animate-delay-ms="0" 
    animate-infinitely="true" 
    animate-in="rubberBand" 
    animate-out="lightSpeedOut"
    >
    <p>Lizards are a widespread group of squamate reptiles, with approximately over 6,000 species ranging across all continents except Antarctica.</p>
</animation-context>

<script>
    riot.mount('animation-context');
</script>
```

## Copyright and license
Copyright (c) 2015 any-code qrb <lee@anycode.io>

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.
