# Proof by Cases

- Proof something by breaking it up into pieces that are easy to proof
  - but in combination include all cases

Example:

```javascript
if((x > 0) || (x<=0 && y > 100))
```

improvement:

```javascript
if(x > 0 || y > 100)
```
