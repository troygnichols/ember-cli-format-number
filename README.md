# Ember-cli-format-number

This README outlines the details of collaborating on this Ember addon.

## Usage

in JS:

```javascript
import numeral from 'numeral';

numeral(100).format('0,0');
```

in templates:

```handlebars
<span>
  {{format-number 100 format="0.0"}}
</span>
```

## Installation

* `git clone` this repository
* `npm install`
* `bower install`

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).
