## Random numbers in MakeCode

Some randomness can help make your programs a bit different every time they run, which adds to the excitement. 

You can find the `pick random`{:class='microbitmath'} block in the `Math`{:class='microbitmath'} menu of your Toolbox.

<img src="images/random-location.png" alt="The Math menu open, with the 'pick random' block highlighted." width="350"/>

Change the `0` and `10` to the range you want your random numbers to take.

To use the random number in your program, you will also have to create a `Variable`{:class='microbitvariables'} to hold your random number. 

```microbit
let tune = 0
input.onGesture(Gesture.Shake, function () {
    tune = randint(1, 4)
})
```
