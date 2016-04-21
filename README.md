# Ember-calendly [![Build Status](https://travis-ci.org/levanto-financial/ember-calendly.svg?branch=master)](https://travis-ci.org/levanto-financial/ember-calendly)

Easy [Calendly](https://calendly.com/) integration for Ember.js apps.

**[FASTBOOT](http://ember-fastboot.com) COMPATIBLE**

## Use

```
ember install ember-calendly
```

Then you have three options for embedding calendly.

### Inline

```hbs
{{calendly-inline
  url='https://calendly.com/mnorth'
  style=(hash
    min-width='320px'
    height='580px')}}
```

### Popup Widget

```hbs
{{calendly-popup-widget
  url='https://calendly.com/mnorth'}}
```


### Popup Text

```hbs
{{calendly-popup-text
  url='https://calendly.com/mnorth'}}
```

## Other stuff

You may also import Calendly as an ES6 module

```js
import Calendly from 'calendly';

Calendly.closePopupWidget();
```

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `npm test` (Runs `ember try:testall` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://ember-cli.com/](http://ember-cli.com/).

&copy; Levanto Financial Inc, All Rights Reserved
