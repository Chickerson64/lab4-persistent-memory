# Vacuum Robot Environment

## Board

The robot operates in the following 4 × 4 grid:
```
 START   0     0     0
   0     X     0     0
   0     0     0     0
   0    -1     0    10
```

Coordinates in this repository use zero-based `(row, column)`, starting at the upper-left.

| Feature | Coordinates |
| --- | --- |
| Start | `(0, 0)` |
| Blocked cell | `(1, 1)` |
| Negative terminal reward | `(3, 1)` |
| Positive terminal reward | `(3, 3)` |



## 
