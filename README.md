# What is this?

Get perfect shadows every time for the non-designer.

# Installation

`npm i @mhy86/shadowizard --save `

Then...

```
import {shadowizard} from '@mhy86/shadowizard';

shadowizard({
    shadow_type: 'soft',
    padding: false
})
```

## Options

Shadowizard supports 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)
