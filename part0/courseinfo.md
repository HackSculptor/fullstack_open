# FUNDAMENTALS OF WEB APPS


## a. General Info
Web development is the process of creating websites and web applications that people can interact with online. It’s like building a digital house, where **front-end development** focuses on the design and user experience, and **back-end development** deals with how things work behind the scenes (like storing data, running logic, etc.).

---

## b. Fundamentals of Web Apps
Web apps are programs that you use through your internet browser (like Chrome or Firefox). Instead of being installed on your computer, they work directly in the browser, allowing you to do tasks like sending emails, chatting with friends, or watching videos.

---

### HTTP GET
HTTP stands for **Hypertext Transfer Protocol**. It’s a set of rules for transferring data over the web. The **GET** method is used to **request data** from a server, like when you type a website address into your browser and it loads the page.

- **Example**: When you visit a website like `https://www.example.com`, your browser sends a GET request to that website’s server to get the page.

---

### Traditional Web Applications
Traditional web applications refresh the entire page every time you interact with them. For example, when you click a link on a webpage, it reloads the page completely to show new content.

- **Example**: If you’re reading an article on a news site and click a new article, the page reloads, and you see a new page.

---

### Running Application Logic in the Browser
JavaScript allows you to run code directly in the browser without needing to reload the page. This makes web pages more interactive.

- **Example**: When you click a button on a webpage, JavaScript can change the page, show a message, or perform an action without reloading the page.

---

### Event Handlers and Callback Functions
- **Event Handlers**: These are functions that wait for something to happen on a webpage, like a user clicking a button or typing a key.
  
  **Example**: If you want a button to do something when clicked, you add an event handler to it.

- **Callback Functions**: After an event happens (like a button click), the callback function is triggered to perform a task.
  
  **Example**: If you want something to happen after a user clicks a button, the code inside the callback function will run.

```javascript
document.getElementById("myButton").onclick = function() {
  alert("You clicked the button!");
};
```

---

### Document Object Model (DOM)
The **DOM** is like a map of all the elements on a webpage (like text, buttons, images, etc.). It lets JavaScript interact with the page and change things on the fly without reloading it.

- **Example**: If you want to change the text inside a paragraph, you can use JavaScript to access and modify that text through the DOM.

```javascript
document.getElementById("myParagraph").innerText = "New text!";
```

---

### Manipulating the Document Object from the Console
The **console** is a tool in web browsers (like Chrome or Firefox) where developers can run JavaScript directly. You can use it to interact with the DOM and make changes to the webpage.

- **Example**: Open the browser’s developer tools (usually by pressing `F12` or `Ctrl+Shift+I`) and use the console to change the page.

```javascript
document.getElementById("title").innerHTML = "Welcome to my website!";
```

---

### CSS (Cascading Style Sheets)
**CSS** is used to style web pages (like changing fonts, colors, and layout). It makes websites look good by defining how elements like text, buttons, and images appear on the page.

- **Example**: You can change the color of text or the size of a button using CSS.

```css
body {
  background-color: lightblue;
}

h1 {
  color: darkblue;
  font-size: 40px;
}
```

---

### Loading a Page Containing JavaScript - Review
When a webpage loads, it can include **JavaScript** to make it interactive. Browsers read the HTML and CSS first to display the page, then run the JavaScript.

- **Example**: A webpage with a button that uses JavaScript to show a pop-up message when clicked.

---

### Forms and HTTP POST
- **Forms** are used on websites to collect information from users (like signing up or submitting a comment). 
- The **POST** method sends data to the server securely, unlike GET, which is visible in the URL.

**Example**: If you fill out a form on a website (like entering your name and email), the data is sent to the server using the POST method.

---

### AJAX (Asynchronous JavaScript and XML)
**AJAX** allows a webpage to load new content **without refreshing** the entire page. It’s often used in applications like social media or email clients where you want new content to appear instantly.

- **Example**: When you scroll down on Facebook and more posts appear, it’s because of AJAX loading new posts in the background.

---

### Single Page Application (SPA)
A **Single Page Application (SPA)** is a web app that doesn't reload the page when you interact with it. Instead, it updates the content on the same page using JavaScript.

- **Example**: Apps like Gmail or Google Maps are SPAs because they let you interact with the app without page reloads.

---

### JavaScript Libraries
A **JavaScript library** is a collection of pre-written code that helps developers build websites faster. One of the most popular libraries is **jQuery**, which makes it easier to work with HTML, CSS, and JavaScript.

- **Example**: Instead of writing long JavaScript code to change the color of a button, you can use a library to do it with one line of code.

```javascript
$("#myButton").css("background-color", "red");
```

---

### Full-Stack Web Development
**Full-stack web development** refers to working with both the **front-end** (what the user sees) and the **back-end** (the server-side, which handles data and logic). A **full-stack developer** can build entire web applications.

- **Example**: Building a website that lets users create an account, view their profile, and send messages would require both front-end and back-end skills.

---

### JavaScript Fatigue
**JavaScript fatigue** is the feeling of being overwhelmed by the many tools, frameworks, and libraries in the JavaScript world. There are constantly new technologies to learn, which can be exhausting for developers.

- **Example**: If you hear about new JavaScript libraries like React, Vue, or Angular every week, it can make it hard to decide which one to learn.

---
