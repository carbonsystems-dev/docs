# Graphite
## STILL IN DEVELOPMENT
## What is it?
Graphite is a JS and TS library made to make the lives of developers easier. We understand that localstorage can be hard for newer devs, so we have worked to fix that issue! Graphite is a feature rich library that allows for seamless integration and ease of access usage of localstorage, allowing for more than what localstorage can do alone. Its very simple to use and I hope you plan on using it for your project

## Usage
First of all, we have to import the library in our head tag:
```js
<script src="https://gitloaf.com/cdn/carbonutilities/graphite/main/graphite.js"></script>
```
Now we can begin using the functions:
### Functions
**Functions save across all pages, so you can set a value on one page and get the value on another.**

`Graphite.set('key', 'value'); or Graphite.set('key', [table, table, table]);`

The Graphite.set function sets a localstorage key and value based on your params. Supports tables.

`Graphite.get('key', function (value) {
        console.log(value); // do anything using the value!
      });` - The Graphite.get functions grabs the value of a specified key.

`Graphite.delete('key');` - The Graphite.delete function deletes a specified key and its value.


#### More coming soon!
