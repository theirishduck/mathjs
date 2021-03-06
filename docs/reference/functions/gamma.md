# Function gamma

Compute the gamma function of a value using Lanczos approximation for
small values, and an extended Stirling approximation for large values.

For matrices, the function is evaluated element wise.


## Syntax

```js
math.gamma(n)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`n` | Number &#124; Array &#124; Matrix &#124; Boolean &#124; null | An integer number

### Returns

Type | Description
---- | -----------
Number &#124; Array &#124; Matrix | The gamma of `n`


## Examples

```js
math.gamma(5);       // returns 24
math.gamma(-0.5);    // returns -3.5449077018110335
math.gamma(math.i);  // returns -0.15494982830180973 - 0.49801566811835596i
```


## See also

[combinations](combinations.md),
[factorial](factorial.md),
[permutations](permutations.md)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->
