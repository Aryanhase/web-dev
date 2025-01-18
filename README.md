# INTERNSHIP PROGRAMME AT EXALTASOFT
# DAY 1
**01-01-2025**

On the first day of training, we learned about the building blocks of web pages called HTML elements.

- We learned how to use different HTML tags to:
    - **Create headings:** Make text appear as headings of different sizes (<h1> to <h6>).
    - **Format text:** Make text bold (<b>), italic (<i>), or emphasize text (<strong>).
    - **Embed media:** Add images, videos, and audio to our web pages.

**The Task: Creating a Signup/Login Page**

Our main task for the day was to create a simple signup/login page. This page included:

- **A form:** This is like an online application.
    - It had fields for:
        - First name
        - Last name
        - Email address
        - Password
- **A submit button:** This button sends the information entered in the form.
- **Links:** These are like clickable buttons that take you to other pages.
    - We created links to "Go to the first page" and "Go to the Second page."

**Key Takeaways**

This task helped us practice using HTML to create forms, input fields, and links for basic navigation between pages. This is essential for building interactive web pages.

# DAY 2

On the second day, we learned how to create lists and tables using HTML.

**Here's what we covered:**

- **Lists:**
    - **Ordered Lists (<ol>):** These are lists with numbers (like numbered steps).
    - **Unordered Lists (<ul>):** These are lists with bullet points.
    - **Definition Lists (<dl>):** These lists are used to define terms.
- **Tables:** We learned how to create tables using tags like <table>, <tr> (table row), <th> (table header), and <td> (table data).

**The Task: Creating Tables and Lists**

Our task was to practice creating these lists and tables to organize our content better.

**Git and GitHub**

We were also introduced to Git and GitHub. These are tools that help us track changes to our projects and work together with others. We were encouraged to use Git to keep track of our work and upload our tasks to GitHub.

**Key Takeaways**

This day's training helped us understand how to structure information using lists and tables, which is essential for creating well-organized and easy-to-read web pages. We also learned about Git and GitHub, which will be valuable for future projects.

# DAY 3

**06-01-2025**

On the third day of training, we learned about **CSS** (Cascading Style Sheets). Think of CSS as the makeup for your website! It's how you make your web pages look attractive and professional.

**Here's what we covered:**

- **Different Ways to Add Styles:**
    - **Inline CSS:** This is like applying makeup directly to your face. You add the style rules right inside the HTML code for each element.
    - **External CSS:** This is like having a separate makeup kit. You create a special file called "styles.css" to store all your style rules, and then link it to your HTML page. This keeps your code organized and makes it easier to update the look of your entire website.
- **Making Things Look Nice:**
    - **Fonts:** We learned how to change the font type, size, and color of text.
    - **Backgrounds:** We learned how to change the background color of elements or even add images as backgrounds.
    - **Centering:** We learned how to center text and other elements on the page.
    - **The Marquee Tag:** This is a special tag that makes text scroll across the screen, like an old-timey news ticker.
- **Targeting Specific Elements:**
    - **Class Selectors:** Imagine you have a group of elements (like all the buttons on your page). Class selectors let you give them a specific name (like "buttonClass") and then apply the same styles to all of them.
    - **ID Selectors:** This is like giving a unique name to a single element (like "mySpecialHeading"). You can then apply very specific styles to that one element.

**The Task: Making the Signup/Login Page with css styling**

For our task, we used CSS to make the signup/login page we created on the first day look much better. We:

- **Styled the Form:** Made the form and the input fields look neat and organized.
- **Added Colors:** Chose attractive background and text colors to make the page more visually appealing.
- **Styled the Button:** Made the submit button look inviting and easy to click.
- **Arranged the Elements:** Made sure the form elements were arranged in a way that was easy for users to understand and use.

**Why This Matters**

Learning how to use CSS is essential for creating websites that are not only functional but also visually appealing. People are more likely to use and enjoy a website that looks good and is easy to navigate.

# DAY 4

07-01-2025

On the fourth day, we dived deeper into CSS by learning about advanced layout techniques:

- **Flexbox:** Imagine arranging items in a flexible row or column. Flexbox gives you powerful control over how these items are spaced and aligned.
- **Grid Layout:** This is like creating a grid on your web page and then placing elements within those grid cells. It's great for complex layouts.
- **Box Model:** We learned how elements on a web page are like boxes with different parts: content, padding, border, and margin. Understanding this helps us control how elements look and behave.

**We also started our JavaScript journey!**

- **What is JavaScript?** We learned that JavaScript is a programming language that makes web pages interactive. It allows things to happen on the user's computer, like responding to clicks or showing animations.
- **How JavaScript Works:** We learned that JavaScript mainly runs on the user's computer (client-side), unlike some languages that run on the server.
- **JavaScript Basics:** We learned the fundamental rules for writing JavaScript code, like how to create variables and functions.
- **First JavaScript Code:** We wrote our very first JavaScript code! It was a simple line that displayed a message to the user.

**Task:**

For the day's task, we practiced using Flexbox and Grid Layout to create different layouts. We also revised the JavaScript basics we learned to solidify our understanding.

# DAY 5

08-01-2025

• On **Day 5** of the training, the focus was on learning **JavaScript concepts** such as variables, scope, operators, strings, and objects. Additionally, **Bootstrap** was introduced for quickly styling and structuring web pages.

**JavaScript Concepts:**

- **Variables and Scope**:
    
    We explored `var`, `let`, and `const` and their behavior in different scopes.
    
    ```jsx
    var a = 10; 
    {
        var a = 20; 
        console.log(a); // Output: 20
    }
    console.log(a); // Output: 20
    ```
    

     

- Demonstrated the **block-scoping** of `let` and `const`.

```jsx
let b = 5;
{
    let b = 10; // Block-scoped, so this does not affect the outer 'b'.
    console.log(b); // Output: 10
}
console.log(b); // Output: 5
```

- **Prompt Input**:

       Used `prompt()` to take user input and performed operations:

```jsx
var a = prompt("Enter a number");
document.write("The number entered is: " + a);
var c = a % 20; // Modulus operation
console.log(c);
```

- **String Operations**:

        Concatenation of strings using `+` and checking conditions using logical operators:

```jsx
let text = "World";
let text2 = "Hello";
let text3 = text + " " + text2; // Concatenates strings
console.log(text3); // Output: World Hello
```

- **Objects**:

        Introduction to JavaScript objects:

```jsx
let name = { firstname: "Pooja", lastname: "Thakral" };
console.log(name.firstname); // Output: Pooja
```

Also,we learned about Bootstrap, a powerful tool that makes web design much easier!

- **What is Bootstrap?**
    - Bootstrap is like a set of ready-made building blocks for your website.
    - It provides pre-designed styles and layouts that you can easily use to make your web pages look good.
    - Instead of writing a lot of CSS code yourself, you can use simple class names provided by Bootstrap.
- **What We Learned:**
    - **Using Bootstrap Classes:** We learned how to use special class names to quickly style text, create grids for arranging elements, and create buttons with different colors and styles (like blue buttons, green buttons, etc.).
    - **Responsive Design:** Bootstrap helps make your website look good on all devices, from small phones to large desktops.
- **The Task:**
    - We put our learning to the test by applying Bootstrap to our signup/login page.
    - We used Bootstrap's grid system to arrange the elements neatly on the page.
    - We styled the buttons, forms, and other parts of the page using the pre-defined Bootstrap components.

# DAY 6

09-01-2025

On Day 6, we delved deeper into JavaScript by learning about:

- **Loops:** These are like repeating actions. We learned about different types of loops:
    - **for loop:** Repeats a block of code a specific number of times.
    - **while loop:** Repeats a block of code as long as a condition is true.
    - **do-while loop:** Similar to while loop, but guarantees that the code block will execute at least once.
- **Conditional Statements:** These allow our code to make decisions. We learned about:
    - **if-else:** Executes code based on whether a condition is true or false.
    - **switch:** Evaluates an expression and executes different code blocks based on the value of the expression.
- **Comparison Operators:** These help us compare values. We learned about:
    - **==:** Checks if two values are equal.
    - **===:** Checks if two values are equal in both value and data type.
    - **!=:** Checks if two values are not equal.
    - **<, >, <=, >=:** Compare values for greater than, less than, greater than or equal to, and less than or equal to.

**Practical Exercises:**

- **Multiplication Table:** We wrote a JavaScript program to generate the multiplication table of any given number. This helped us apply our knowledge of loops.
- **Finding the Largest Number:** We wrote code to compare three numbers and determine which one is the largest. This involved using conditional statements and comparison operators.
- **Even or Odd:** We wrote code to check if a given number is even or odd. This used the modulo operator (%) to check if a number is divisible by 2.

# DAY 7

10-01-2025

On the seventh day, we explored some key JavaScript concepts:

- **Dialog Boxes:** We learned how to create a confirmation box that pops up and asks the user "Are you sure?" before performing an action. This is useful for preventing accidental actions.
- **Arrays:** Arrays are like lists that can hold multiple values. We learned how to work with arrays, such as adding new items, sorting them, reversing their order, and checking how many items they contain.
- **Objects:** Objects are like containers that store information in a key-value format. This is a very powerful way to organize data.
- **Strings:** Strings are pieces of text. We learned how to manipulate strings, such as converting them to uppercase or lowercase, extracting parts of a string, and more.

**Hands-on Practice:**

We put these concepts into practice by:

- **Creating a confirmation dialog box:** We built a simple application that uses a confirmation box to confirm user actions.
- **Manipulating arrays:** We practiced adding and removing items from arrays, sorting them, and reversing their order.
- **Working with objects:** We created JavaScript objects and learned how to access and modify their properties.
- **Manipulating strings:** We used various string methods to change the case of text, extract parts of strings, and perform other string operations.

# DAY 8

11-01-2025

On the eighth day, we had a chance to clear up any doubts we had from the previous days of training.

Then, we got some hands-on practice with the following:

- **Flexbox:** We created a layout using Flexbox, a powerful CSS tool for arranging elements on a page. This helped us understand how to align images and text effectively.
- **JavaScript Arrays:** We learned how to store a list of items in a JavaScript array and then display those items in an alert box.
- **JavaScript Functions:** We wrote a JavaScript function to calculate the factorial of a number. This helped us understand how to create and use functions in JavaScript.

# DAY 9
