# vanillajs-basic-calculator
simple calculator made with vanilla js

The logic of this calculator is pretty simple, I basically just used *querySelectorAll* to get a list of all calculator buttons, which then I iterate to add an *onclick* action listener to each button. When a button is clicked it will return it's *innerText*, which is the label or number of that specific button. Next, I have a function that will process the returned *innerText* or clicked “value”. If any **digit** button is clicked I simply display the value in the input tag. If **DEL** button is clicked I remove the value of the last button clicked, else if **AC** is clicked I clear all previous values. Finally, when **=** is clicked I use regex to format the expression, which then is evaluated and the result is displayed.

### Demo:
[https://calculatordemo.gspinoza.repl.co/](https://calculatordemo.gspinoza.repl.co/)
<img src="https://github.com/gspinoza/vanillajs-basic-calculator/blob/master/calculator-screenshot.jpg?raw=true" width="100%"></img>

