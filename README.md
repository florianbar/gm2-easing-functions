# Game Maker 2 - Easing functions

## Any transitional change
```
EaseLinear(time, start, change, duration);
EaseIn(time, start, change, duration);
EaseInOut(time, start, change, duration);
EaseOutElastic(time, start, change, duration);
```

## Movement specific change (From A to B)
```
EaseLinearExt(time, startX, startY, endX, endY, duration);
EaseInExt(time, startX, startY, endX, endY, duration);
EaseInOutExt(time, startX, startY, endX, endY, duration);
EaseOutElasticExt(time, startX, startY, endX, endY, duration, tension); //added tension to control bounciness
```
