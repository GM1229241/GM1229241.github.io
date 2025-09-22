# My Coding Notebook

## Table of Contentes 
  - [Flutter Notes](#flutter-notes)
  - [what is Flutter?](#what-is-flutter)
  - [Key Terms and Definitions](#Key-terms-and-definitions)
  - [Layout and Design Widgets](#layout-and-design-widgets)
  - [Definitions with Structures](#flutter-definitions)
  - [Code Definitions](#code_definitions)
  - [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)

## 

### What is Flutter?
- Definition:
- Why is it useful?

---

### Key Terms and Definitions

| Term             | Definition                                      | Example / Notes                          |
|------------------|--------------------------------------------------|-------------------------------------------|
| Widget           |Basic building block of a Flutter app. Everything is a widget|              |
| MaterialApp      |The root of the app. Sets up routes and themes|                             |
| Scaffold         |Provides basic visual layout-like a header, body, floating button|          |
| StatelessWidget  |A Widget that dosnt change|                                                 |
| StatefulWidget   |A widget that can change over time|                                         |
| Navigator        |Manages screen transitions|                                                 |
| AppBar           |Top navagation bar|                                                         |
| Column           |Vertical layout|                                                            |
| Row              |horizontal layout|                                                          |
| Container        |Wraps content with padding, margin, or color|                               |
| Text             |Displays text|                                                              |
| Image.network    |  |                                                                         |

| Padding    |                    |                                                             |

| Center      |                    |                                                            |











## Flutter Definitions

| Term | Definition and Description | Base Structure | Real Life Example | App Example |
|------|----------------------------|----------------|-------------------|-------------|
| Main | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` |  | in Main.dart void main() => runApp(MyPortfolioApp());|
| MaterialApp | The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` |  |  |
| Scaffold | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |  | in Showcae.dart |
| Column | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |  |  |
| Row | A widget that shows things side-by-side. | `Row(...)` |  |  |
| Container | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |  |  |
| Text | A widget to display text on the screen. | `Text('Hello')` |  | in alt_design_screen.dart  "text": "Bella is a calm and loyal companion who enjoys long naps.", |
| Image.network | A widget to show an image using a link from the internet. | `Image.network('https://...')` |  |  |
| ElevatedButton | A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` |  |  |
| onPressed | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |  | in showcaes.dart  onPressed: () => Navigator.pushNamed(context, '/alt'), |
| StatelessWidget | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` |  |  |
| Navigator | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |  | in alt_design_screen.dart class AltDesignScreen extends StatelessWidget { |
| @override | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |  | in main.dart class MyPortfolioApp extends StatelessWidget {@override |
| build() | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` |  | in background.dart  padding: const EdgeInsets.only(left: 100.0),in
|
| BuildContext | Aligns content in the center of the screen or container. | `Center(child: ...)` |  |  |
| Super.key | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  |  |
| const | This marks a method as one that’s replacing a method in a parent class. | `@override` |  | in home.dart @override |
|  | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  | in alt_design_screen.dart  Widget build(BuildContext context) { |
|  | Required in every widget class to describe what to show. | `build` |  |  |
|  | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |  |  |
|  | A keyword used to pass a value to the parent widget. | `super.key` |  |  |
|  | A keyword that means the value won't change and is set once. | `const` |  |  |








## Code Definitions
| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
| Variable | A named container used to store a value that may change. | `var x = 5;` |  |  |
| Constant | A fixed value that cannot change once set. | `const PI = 3.14;` |  |  |
| Data Type | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |  |  |
| String | A sequence of characters used to represent words or text. | `"Hello World"` |  |  |
| Integer | Whole number values. | `int age = 16;` |  |  |
| Double | Number values with decimals. | `double age = 16.2;` |  |  |
| Boolean | A value that can be true or false. | `bool isLoggedIn = false;` |  |  |
| List | A collection of values in a specific order. | `List<String> names = [];` |  |  |
| Null | A special value that means “nothing.” | `String? name = null;` |  |  |
| Function | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |  |  |
| Parameter | The information passed into a function to change how it works. | `greet(String name)` |  |  |
| Return | The result a function gives back. | `return total;` |  |  |
| Scope | Where a variable or function can be used. | (No set syntax — concept-based) |  |  |
| Class | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |  |  |
| Object | A specific version of a class. | `Dog myDog = Dog();` |  |  |
| Property | A variable that belongs to a class/object. | `String name;` |  |  |
| Method | A function that belongs to a class. | `void bark() {}` |  |  |
| Constructor | A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |
| Abstraction | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |
| Override | Changing how a built-in or inherited function behaves. | `@override` |  |  |
| Void | A function that does not return a value. | `void printMessage() {}` |  |  |
