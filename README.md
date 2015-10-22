# React Helpers

```
npm i react-helpers --save-dev
```

## Methods

### `filterProps`

The `filterProps` method allows you to specify a prefix and create an object that only contains properties with that prefix, it will also lower-case the value of the string without that prefix. Let's run through the example below.

```js
var props = {
  inputOnChange: true,
  formOnSubmit: true
}

var inputProps = filterProps(props, 'input')
/*
{
  onChange: true
}
*/
```
