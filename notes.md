# Design Patterns

## Model View and Controller
- **Model** - The model represents data and the rules that govern access to and updates of this data. In enterprise software, a model often serves as a software approximation of a real-world process.
- **View** - The view renders the contents of a model. It specifies exactly how the model data should be presented. If the model data changes, the view must update its presentation as needed.
- **Controller** -  The controller translates the user's interactions with the view into actions that the model will perform. 
- [MVC Example Tutorial](http://www.cs.utsa.edu/~cs3443/mvc-example.html)
- [Calculator MVC documentation](http://www.cs.utsa.edu/~cs3443/demomvc/calculator/index.html)
- "MVC uses other design patterns, such as Factory Method (121) to specify the default
controller class for a view and Decorator (196) to add scrolling to a view. But the
main relationships in MVC are given by the **Observer**, **Composite**, and **Strategy** design
patterns"
- [Observer](https://refactoring.guru/design-patterns/observer)
- [Composite](https://refactoring.guru/design-patterns/composite)
- [Strategy](https://refactoring.guru/design-patterns/strategy)
