# CVS
A design pattern!

CVS is a poorly hashed out design pattern with what I hope are some interesting ideas
CVS stands for:
- Controller (state/action management solution)
- View (render from props, attach event listeners)
- Signal (passing messages with external entities)

Why did I choose this name? Because I'm a stupid hipster who makes really dumb jokes

CVS is based on two core ideas:
- Asynchronous actions and distributed state are a fundamental constraint on web applications, and should be handled distinctly.
- The view, controller, and AJAX solutions should be swappable, and therefore should have a very rudimentary to understand interface.

Additionally:
- I want to be able to use current toolchains within CVS that work, aka React and Redux.
- I want to dissuade the idea that sagas are a good paradigm
- I want to make a really dumb joke

C provides scoped tuple (action, props) to the view.
V takes props, renders, and applies listeners for actions.
S is a poorly constructed idea. Let's work on it otherwise.
