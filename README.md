# Counter_7
# Julian Justin Orvino
## Explain whats the meaning by stateless widget and the difference between them

### Stateless widget

Stateless immutable meaning that it cannot be changed. The component and properties remain unchanged. It means the widgets cannot be changed while the application is running.

### Stateful Widget

While Stateful Widget Is mutable widget, it means that can be changed through the run time of the application. Appearance could be change according the request and then sent it back in a form of response.

### Mention the widgets you use in this project and explain their functions.
- Text : Display string
- AppBar : Display toolbar widgets
- Scaffold :As foundation structure and styling.
- Column : Display children in a vertical format.
- Row : Display children in a horizontal format.


### What is the function of setState()? Explain what variables can be affected by the function.

to change the UI of stateful widget, we need to use setState() funct because it will allow us to change the UI of stateful widget. The affected by setState() function are the variables that are going to be changed.

### Explain the difference between const and final.

Final be used to declare the variables that are immutable, it means values that are/aren't known by compile time, while const can be used to declare immutable variables that the values are constant and must be known at compile time, it means that the value of the variable must've been assigned a value directly.

### How You implement the checklist above
- Add new function named _setText() to set the text (_written) for "EVEN" and "ODD" 
- Add a function _decrementcounter to decrement the number according the counter below the increment one.
- Use the interface to design the widget and set the color of odd to blue and even to red
- Push to github.