# Micro LED

## Create Shake Gesture
Drag the code to from input-On Shake Gesture

```blocks
input.onGesture(Gesture.Shake, function () {
    
})
```

### Toggle an LED

Drag the code from LED. Then toggle x and y coordinates

```blocks
input.onGesture(Gesture.Shake, function () {
    led.toggle(0, 4)
    led.toggle(4, 3)
    led.toggle(4, 4)
    led.toggle(2, 0)
    led.toggle(2, 1)
    led.toggle(2, 2)
    led.toggle(2, 3)
    })
```


