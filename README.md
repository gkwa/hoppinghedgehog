# hoppinghedgehog

Use testscript to verify that this removes code blocks from scripts.

```
exec perl -0777 -i -pe 's/```.*?```\s*//gs' sample1.py
```


```
# usage
just test
```
