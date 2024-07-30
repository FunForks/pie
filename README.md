# This puzzle has no JavaScript #

[Demo](https://funforks.github.io/pie)

It uses radio buttons, the ~ sibling selector, a different ordering for inputs and the labels that are associated with them, and a series of span elements that hide the green div that shows you have the right answer... unless all your choices are right.

There's also an animation which uses a counter and ::before and ::after pseudo elements to create a countdown timer and the illusion that time is running out. The ::before element fills the viewport and blocks all further pointer events when the animation reaches 100%.

Basic settings are made with custom CSS properties.

Enjoy!