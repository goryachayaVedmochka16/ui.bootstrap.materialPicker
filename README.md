# ui.bootstrap.materialPicker

Material Design Color Picker directive for AngularJS.

[![Color Picker](http://i.imgur.com/k1YbW7f.png)](http://codepen.io/templarian/pen/jPyvpv)

Latest codepen.io [example](http://codepen.io/templarian/pen/jPyvpv).

## Reference the `ui.bootstrap.materialPicker` module

To use include the `ui.bootstrap.materialPicker.js` file and add a reference to the `ui.bootstrap.materialPicker` module.

## Tag

```html
<material-picker ng-model="color"></material-picker>
<material-picker ng-model="color" format="'hex'" size="10" hover-model="hoverColor" size="15"></material-picker>
```

| Attribute   | Default    | values          | Required |
|-------------|------------|-----------------|----------|
| ng-model    | n/a   | string, object       | true |
| hover-model | n/a        | object          | false |
| format      | `'object'` | 'object', 'hex' | false |
| size        | `15`       | `5` to n        | false |

## CSS

The required CSS is below.

```css
.colorpicker-colors {
  -webkit-user-select: none;
  user-select: none;
  position: relative;
  border: 1px solid #FFF;
  border-radius: 2px;
  display: inline-block;
  box-shadow: 0 1px 5px rgba(0,0,0,0.5);
  cursor: default;
}
.colorpicker-colors div.selected {
  position: relative;
  z-index: 2;
  box-shadow: 0 0 4px #000;
  border: 2px solid #FFF;
}
div.colorpicker-white.selected {
  border-color: #78909C;
}
```
