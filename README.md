# jQ Query Builder Elasticsearch

### Dependencies
 * jQuery QueryBuilder >= 2.0

## Usage

The plugin adds a new public method to all QueryBuilder instances.

### getESBool

Performs validation and returns the rules as a valid Elasticsearch bool query.

```js
var esQuery = $('#builder').queryBuilder('getESBool');
```

### Operators configuration

The Elasticsearch plugin requires special configuration for operators to convert rules. This configuration is stored in the ```ESBoolOperators``` option, see the source code for more details.

## Dev

### Run tests

`$ grunt test --verbose`
