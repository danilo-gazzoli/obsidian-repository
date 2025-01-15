# What is MVC Pattern?

The MVC pattern is a [[Software Architectural Pattern]] to make applications more structured, scalable, maintainable and helps developers keep the project more organized. The MVC divide the project in three parts:

## **Models**

The models represents the data and business logic application. It's responsible of retrieving, storing and processing data, make interactions with database and API's.

## **Views**

The views are the [[User Interface (UI)]] of application. It represents the output that the users interacts with displaying data that the model provides and send user inputs to the controller. 

## **Controllers**

The controller acts as an between models and views. It handles user inputs of View, updates the Model based on user actions and determines which View to display and updates it.

# Why is MVC Better Compared to Other Patterns?

1. **Separation of Concerns**: The key advantage of MVC is that it separates the data (Model), the UI (View), and the logic (Controller). This allows you to modify one part without affecting the others. For example, you can update how the data is displayed in the View without changing the logic in the Controller or the Model.
    
2. **Easier Maintenance**: Since each part has a clear responsibility, developers can focus on a specific part of the code without worrying about the whole system. If you need to add a new feature, you know exactly where to make changes.
    
3. **Testability**: Testing is easier because the Model, View, and Controller are separated. You can test the Model independently from the View and Controller, making the process faster and more efficient.
    
4. **Scalability**: MVC allows your application to grow in a manageable way. As your app gets bigger, it becomes easier to maintain because the architecture ensures that components are loosely coupled.

## [[Ruby]]'s Performance with [[Clean Architecture]]

Ruby is a very simple programming language because is an [[Interpreted Language]]  and not a [[Compiled Language]].

Ruby can provide a fast development, especially when using [[Ruby on Rails]]. However, the clean arch can add more complexity, due to any layers and abstractions, causing performance issues. 

