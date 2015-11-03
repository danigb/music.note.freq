## `freq`

Get the pitch frequency in herzs with custom concert tuning

This function is currified so it can be partially applied (see examples)

### Parameters

* `tuning` **`Float`** the frequency of A4 (null means 440)
* `note` **`String or Array`** the note name


### Examples

```js
freq(null, 'A4') // => 440
freq(444, 'A4') // => 444
```
```js
// partially applied
['A4', 'A#4', 'B5'].map(freq(440)) // => [440, ...]
var baroque = freq(415)
baroque('A3') // => 207.5
```

Returns `Float` the frequency of the note
