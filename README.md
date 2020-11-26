# braintapper-svelte-indent

A simple indent div that I use for hierarchical list views.

## Usage

### Component Import

Import the components you need in your `<script>` tag:

```
  import { Indent } from "braintapper-svelte-indent";
```

### Example Markup

```
  <Indent level={indentation} width={32} offset={48}/>
```


### Flex Prop Values

#### level (integer)

Level is the depth of the indent. 

#### width (integer)

The width of each indent level in `px`

#### offest (integer)

The offset of the indent in `px`. Offset is used when you may have an icon or other item at the start of the line that you may need to account for.

---

License: MIT