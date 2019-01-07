```
when green flag clicked
forever
wait (0.1) seconds
next costume
end
```

```
when green flag clicked
set rotation style [left-right v]
forever
move (10) steps
turn cw (pick random (1) to (10)) degrees
if on edge, bounce
end
```