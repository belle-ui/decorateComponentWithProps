A simple function to decorate your component with miscellaneous props:

Example:

```js
import decorateComponentWithProps from 'decorate-component-with-props';

const props = {
  wine: 'red',
  beer: 'ipa',
  food: 'spaghetti',
};

MyDecoratedComponent = decorateComponentWithProps(MyComponent, props);

// MyDecoratedComponent will now be decorated with these props
```
