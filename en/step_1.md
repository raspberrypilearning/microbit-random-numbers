## Random numbers in MakeCode

A bit of randomness can help make your programs a little bit different every time they run, how exciting!

You can find the `pick random`{:class='microbitmath'} block in the `Math`{:class='microbitmath'} menu of your Toolbox.

<img src="images/random-location.png" alt="The Math menu open, with the 'pick random' block highlighted" width="350"/>

Change the `0` and `10` to the range you want your random numbers to take.

In order to use it in your programs you will have to create a `Variable`{:class='microbitvariables'} to hold your random number. 

```microbit
let tune = 0
input.onGesture(Gesture.Shake, function () {
    tune = randint(1, 4)
})
```