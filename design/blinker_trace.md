### blinker trace

### generation 0

live cells:
- (4,10)
- (5,10)
- (6,10)

grid (rows 3-7, cols 8-12)

```text
. . . . .
. . O . .
. . O . .
. . O . .
. . . . .
```

neighbor counts

```text
0 1 1 1 0
0 2 1 2 0
0 3 2 3 0
0 2 1 2 0
0 1 1 1 0
```

When applying the rules, it gives generation 1

---

### generation 1

Live cells:
- (5,9)
- (5,10)
- (5,11)

Grid (rows 3-7, cols 8-12)

```text
. . . . .
. . . . .
. O O O .
. . . . .
. . . . .
```

Neighbor Counts

```text
0 0 0 0 0
1 2 3 2 1
1 1 2 1 1
1 2 3 2 1
0 0 0 0 0
```

When applying the rules, it gives Generation 2.

---

## Generation 2

Live cells:
- (4,10)
- (5,10)
- (6,10)

Grid (rows 3-7, cols 8-12)

```text
. . . . .
. . O . .
. . O . .
. . O . .
. . . . .
```

The blinker has returned to its original vertical shape after two generations.
```
