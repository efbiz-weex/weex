# Special Element
<span class="weex-version">0.4</span>

## &lt;content&gt;

The element serves as content distribution outlet in a composed component template. The element itself will be replaced.

alias: `<slot>`

### Code Example

```html
<we-element name="item">
  <template>
    <div>
      <content></content>
    </div>
  </template>
</we-element>

<template>
  <div>
    <item>
      <text>Content Text</text>
    </item>
  </div>
</template>
```

