#  Challenge Accepted 01: Animation

The goal of this challenge is to create a system that allows you to animate a transition between 2 numbers. When the user taps the "Start" button, the app should smoothly animate between any two numeric values over a fixed timespan. 

### Parameters

Your solution should accept 3 values, which should be easily setable within your code:

- `startValue`: The starting value. Can be an integer or floating point number.
- `endValue`: The ending value. Can be an integer or floating point number.
- `duration`: The length of the animation, in seconds.

### Bonus Objectives

Here are some optional goals you could incorporate to make a more robust solution:

1. **Easing** – Smooth the animation by having it speed up at the start and slow down at the end (also known as ease-in-out). Read more about easing functions here: [Easing Functions](http://robertpenner.com/easing/)
2. **Toggle Int/Float Mode** – Allow the user to pick whether they want to see only rounded integers or fractional values. Fractional values should be limited to a single digit of precision.
3. **Stabilize Numeric Display** – Having the displayed number jiggle around as the widths of the individual digits change is distracting and inelegant; modify the display so that the number remains motionless during animation. We want to maintain design consistency, so changing the font is not allowed. *Hint: Check out [this WWDC talk](https://developer.apple.com/videos/play/wwdc2015/804/) to learn more about the advanced features of the San Francisco font.*
