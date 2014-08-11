# metasyntactic-variables

implements [rfc3092](http://www.faqs.org/rfcs/rfc3092.html), providing the
standard list of metasyntactic variables used in syntax examples

# example

``` js
var variables = require('metasyntactic-variables');
console.log(variables.join('\n'));
```

output:

```
foo
bar
baz
qux
quux
corge
grault
garply
waldo
fred
plugh
xyzzy
thud
```

# data

``` js
var variables = require('metasyntactic-variables')
```

## variables

An array of the 13 standard (rfc3092) metasyntactic variables.

# install

With [npm](https://npmjs.org) do:

```
npm install metasyntactic-variables
```

# license

MIT
