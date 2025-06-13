# state management using redux

Redux allows us to maintain a global state for our applications that can be used across multiple components without prop drilling just like ContextAPI, but for large scale applications . For our application, we have a Header component, which is completely different from our CounterApp component (mapped to the route /counter-app). We want to achieve a feature such that when a button is clicked in one component, the effect can reflect in another component
