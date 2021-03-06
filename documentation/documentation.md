<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

# Foo

Foo Class

## constructor

This function returns listings based on a geographic region.

**Parameters**

-   `name` **\[[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)](default '')** any string.

## bar

This function prints a pointless string.

**Parameters**

-   `str` **\[[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)](default 'bar')** any string.

Returns **[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)** phrase appending string.

## baz

This function returns a pointless number.

**Parameters**

-   `n` **\[[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)](default 3)** any number.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** new number.

# Listing

Listing Class

## constructor

This function returns listings based on a geographic region.

**Parameters**

-   `name` **\[[string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)](default '')** any string.

## fetchListingData

This function returns listings based on a geographic region.

**Parameters**

-   `callback` **[function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function)** any function.

Returns **[object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)** listing data.

# 

**Examples**

```javascript
import { Listing } from 'moxi-jsapi';
const listing = new Listing('listings');
const listings = listing.fetchListingData((res) => {
  return res;
});
```
