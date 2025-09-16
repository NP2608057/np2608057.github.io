# My coding notebook

## Table of Contents
- [Flutter notes](#day-1)
   -[What is flutter](#notes)      
  - [Key terms and Definitions](#practice)     
  - [layout and design widgets](layout-and-design-widgets)
  - [definitions with structures](#flutter-definitions)
  -  [Flutter Definitions](#flutter_definitions)  
  -
[Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)






### 🧱 What is Flutter?
- Definition: A frame work made by google for building apps that work on web,Android, and IOS-with one codebase
- Why is it useful? Uses the Dart programming language and helps save time and money

---

### 🧩 Key Terms and Definitions

| Term             | Definition                                      | Example / Notes                          |
|------------------|--------------------------------------------------|-------------------------------------------|
| Widget           |Basic building block of a flutter app.Everything is a widget text. image,container, colum                                              |                                           |
| MaterialApp      |The root of the app , Srts up routes and themes                                                  |                                           |
| Scaffold         |Provides basic visual layouts-like header, body , floating button                                                  |                                           |
| StatelessWidget  |Predefined paths to navigate between screens                                                  |                                           |
| StatefulWidget   |                                                  |                                           |
| Navigator        |                                                  |                                           |
| AppBar           |Top navigation bar                                                   |                                           |
| Column           |Vertical layout                                                  |                                           |
| Row              |Horizontal layout                                                  |                                           |
| Container        |Wraps content with padding, margin , or color                                                  |                                           |
| Text             |Displays text                                                  |                                           |
| Image.network    |Displays images from a URl                                                  |                                           |
| Padding          |                                                  |                                           |
| Center           |                                                  |                                           |
---



### Layout and Design Widgets
- How do you center a widget?
- How do you align something to the left or right?
- What widget adds space around content?


## Flutter Definitions

| Term | Definition and Description | Base Structure | Real Life Example | App Example |
|------|----------------------------|----------------|-------------------|-------------|
|      | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` |  |  |
|      | The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` |  |  |
|      | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |  |  |
|      | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |  |  |
|      | A widget that shows things side-by-side. | `Row(...)` |  |  |
|      | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |  |  |
|      | A widget to display text on the screen. | `Text('Hello')` |  |  |
|      | A widget to show an image using a link from the internet. | `Image.network('https://...')` |  |  |
|      | A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` |  |  |
|      | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |  |  |
|      | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` |  |  |
|      | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |  |  |
|      | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |  |  |
|      | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` |  |  |
|      | Aligns content in the center of the screen or container. | `Center(child: ...)` |  |  |
|      | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  |  |
|      | This marks a method as one that’s replacing a method in a parent class. | `@override` |  |  |
|      | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  |  |
|      | Required in every widget class to describe what to show. | `build` |  |  |
|      | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |  |  |
|      | A keyword used to pass a value to the parent widget. | `super.key` |  |  |
|      | A keyword that means the value won't change and is set once. | `const` |  |  |

[Code Definitions](#code-definitions)

| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
|Variable      | A named container used to store a value that may change. | `var x = 5;` | Student ages 15  | |
|Constant      | A fixed value that cannot change once set. | `const PI = 3.14;` |The title  ||
|Data type      | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |Number of Mearsurements vs A name  |  |
|String      | A sequence of characters used to represent words or text. | `"Hello World"` |Filtering spam emails  |  |
|Integer      | Whole number values. | `int age = 16;` | A team/sports score  |  |
|Double      | Number values with decimals. | `double age = 16.2;` | Math for data analysis  |  |
|Boolean      | A value that can be true or false. | `bool isLoggedIn = false;` | Online forms that check for verification/valid input  |  |
|List      | A collection of values in a specific order. | `List<String> names = [];` | Information on User   |  |
|Null      | A special value that means “nothing.” | `String? name = null;` |A loading level |  |
|Function      | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |Buisness software  |  |
|Parameter      | The information passed into a function to change how it works. | `greet(String name)` |Video game characters customization  |  |
|Return      | The result a function gives back. | `return total;` | Smart devices  |  |
|Scope      | Where a variable or function can be used. | (No set syntax — concept-based) | Cyber security  |  |
|Class      | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` | Template for creativity  |  |
|Object      | A specific version of a class. | `Dog myDog = Dog();` | A type of car  |  |
|Property      | A variable that belongs to a class/object. | `String name;` | Screen size  |  |
|Method      | A function that belongs to a class. | `void bark() {}` | A traffic light  |  |
|Constructor      | A special function used to set up a class when it’s created. | `Dog(this.name);` |Meals that are pre-packaged  |  |
|Abstraction      | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) | A remote control  |  |
|Override      | Changing how a built-in or inherited function behaves. | `@override` | A circle and rectangle overriding  |  |
|Void      | A function that does not return a value. | `void printMessage() {}` |"print this document" or "turn on the light"|  |

   
[Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)
## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  
This ensures your notes are easy for you (and others) to read later.

---

## 🔹 Headings
**When to use:** Organize your notebook into sections (like days, topics, or projects).  
- `#` for the notebook title (use once at the top).  
- `##` for each day or major topic.  
- `###` for subsections (like "Notes", "Practice", "Reflections").  

✅ Example:


# My Coding Notebook
## Day 1
### Notes
### Practice

🔡 Text Formatting
When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

✅ Example:

**Class** = a blueprint for objects  
*Remember:* always test your code  
Use `System.out.println()` to print

 

💻 Code Blocks
When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

✅ Example:

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

🧾 Lists
When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

✅ Example:

1. Define the class
2. Write the main method
3. Test your program

Variables
- Loops
- Conditionals
 

✅ Checklists
When to use: Track progress on assignments or tasks.

✅ Example:

[x] Complete coding warm-up
- [ ] Finish project draft
- [ ] Reflect on learning

 

➡️ Blockquotes
When to use: Call out notes, reminders, or teacher comments.

✅ Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

📊 Tables
When to use: Compare values, track progress, or organize data neatly.

✅ Example:

| Task        | Status   | Notes          |
|-------------|----------|----------------|
| Homework 1  | Done ✅  | Submitted      |
| Homework 2  | Pending  | Needs review   |

 

🔗 Links & Images
When to use: Add references, resources, or visuals.

✅ Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  
![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

 

📂 Collapsible Sections
When to use: Hide solutions, extended notes, or extra details.

✅ Example:

<details>
  <summary>Click to reveal solution</summary>
  
System.out.println("Answer: 42");

</details>

 

📝 Footnotes
When to use: Add references or side notes without cluttering the page.

✅ Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

🎯 Style Rules
Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

✅ Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.



