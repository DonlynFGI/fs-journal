# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
abstraction, inheritance, encapsulation, poymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
property.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
writing code in such a way that people cannot directly modify values or code, but instead must pass their changes through an independent handler of sorts.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single-Responsibility Principle.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
the class is the entire code segment written, whereas an instance of a class is where we call/mention the stored class for use
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
an object that can be passed to the appdata without directly modifying it
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
To secure our code from users being able to directly modify or "cheat"
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
to handle signals sent by the user and to pass them on to the service code.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
to handle business logic and modify data in the code before passing it back up the chain
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
the model allows us to define a structure or template for data that will inevitably be passed through the code, so that the system is already aware of how to format and utilize said data.
```
