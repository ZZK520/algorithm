```
{
 a: {
        b: 1,
        c: 2,
        d: {e: 5}
    },
 b: [1, 3, {a: 2, b: 3}],
 c: 3
}

```
转成
```
 {
  'a.b': 1,
  'a.c': 2,
  'a.d.e': 5,
  'b[0]': 1,
  'b[1]': 3,
  'b[2].a': 2,
  'b[2].b': 3
   c: 3
 }
```