# iOS VIPER

#### What is VIPER?

VIPER is an architectural pattern like MVC or MVVM, but it separates the code further by single responsibility. Apple-style MVC motivates developers to put all logic into a UIViewController subclass. VIPER, like MVVM before it, seeks to fix this problem.

Each of the letters in VIPER stand for a component of the architecture: View, Interactor, Presenter, Entity and Router.

- The View is the user interface. This corresponds to a SwiftUI View.
- The Interactor is a class that mediates between the presenter and the data. It takes direction from the presenter.
- The Presenter is the “traffic cop” of the architecture, directing data between the view and interactor, taking user actions and calling to router to move the user between views.
- An Entity represents application data.
- The Router handles navigation between screens. That’s different than it is in SwiftUI, where the view shows any new views.

This separation is borne out of “Uncle” Bob Martin’s Clean Architecture paradigm.

<img src="https://koenig-media.raywenderlich.com/uploads/2020/02/viper.png">

Source: https://www.raywenderlich.com/8440907-getting-started-with-the-viper-architecture-pattern

Documentations: 

- https://medium.com/@smalam119/viper-design-pattern-for-ios-application-development-7a9703902af6
- https://medium.com/cr8resume/viper-architecture-for-ios-project-with-simple-demo-example-7a07321dbd29
