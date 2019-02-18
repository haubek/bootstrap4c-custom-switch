# Bootstrap4C

### Custom switch

The *Custom switch* is a simple Bootstrap 4 component that turn your default HTML checkbox inputs `<input type="checkbox">` into beautiful iOS style switches — and allow you to display different content depening on the `checked` attribute. The component is 100% CSS, no JavaScript.

See demo here => https://haubek.github.io

### Yarn install

```
yarn add bootstrap4c-custom-switch
```

### CSS

```
<link href="path/to/component-custom-switch.css" rel="stylesheet">
```

### HTML5 markup

See `example.html` for all markup examples.

```
<div class="custom-switch">
  <input class="custom-switch-input" id="ADD_ID_HERE" type="checkbox">
  <label class="custom-switch-btn" for="ADD_ID_HERE"></label>
</div>
```

```
<div class="custom-switch custom-switch-label-yesno">
  <input class="custom-switch-input" id="ADD_ID_HERE" type="checkbox">
  <label class="custom-switch-btn" for="ADD_ID_HERE"></label>
  <div class="custom-switch-content-checked">
    I'm checked
  </div>
  <div class="custom-switch-content-unchecked">
    I'm unchecked
  </div>
</div>
```
