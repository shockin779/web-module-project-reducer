# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
2. The onClick event is called that calls a local funtion on the app.
3. The app then calls the action for the event to create the dispatch object {type: (required), payload: (optional)}
4. Then the dispatch function is called passing the newly created objct.
5. This then goes to the reducer and modifies the state of the object.
6. After this, the new state object gets returned and that cause the render to be ran using the new state values.

* TotalDisplay shows the total plus 1.
