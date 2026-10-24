Lab 4b: Client-Side Scripting (JSON and jQuery)

Name: Adam Shahputra Bin Halim  
Matric Number: AI250069  
Course: BIC21203 Web Development

Introduction

This lab focuses on using JSON, JavaScript `fetch()`, and jQuery to develop web pages and manipulate HTML elements.

Question 1

Concepts Used:
•	JSON (JavaScript Object Notation): A format used to store and organize data.
•	Objects: Store information about each book.
•	Arrays: Store multiple books and their genres.
•	Data types: Strings for titles and authors, numbers for publication years, and arrays for genres.
•	SON syntax: Uses double quotation marks and does not allow trailing commas.

How to Run:
•	Open Visual Studio Code.
•	Open your Lab4b project folder.
•	Open the books.json file.
•	Check that the file contains two book objects with the correct titles, authors, publication years, and genres.
•	Save the file.
•	To view the JSON data in a browser, start Live Server and open books.json, or click the file from the Live Server directory listing.

Expected Result:
The browser or editor displays the JSON data for:
•	The Great Gatsby
•	To Kill a Mockingbird
The JSON file should contain valid data and follow the required structure.

Question 2

Concepts Used:
•	Fetch API: Retrieves data from the books.json file.
•	async/await: Handles asynchronous operations.
•	JSON parsing: response.json() converts the response into a JavaScript object.
•	DOM manipulation: createElement() creates HTML elements dynamically.
•	textContent: Displays text safely on the webpage.
•	Error handling: try/catch handles errors when loading or reading the JSON data.
•	Local development server: Live Server allows the HTML page to retrieve the local JSON file.

How to Run:
•	Open Visual Studio Code.
•	-Open your Lab4b project folder.
•	Make sure books.html and books.json are in the same folder.
•	Open books.html.
•	Right-click inside the editor and select Open with Live Server.
•	Your browser will open the webpage.
•	Check that the required book information is displayed.
Important: Do not open books.html directly using file://. Use Live Server to run the page.

Expected Result:
The webpage displays:
•	First book title: The Great Gatsby
•	Second book author: Harper Lee
•	The Great Gatsby - Fiction, Classics
•	-To Kill a Mockingbird - Fiction, Coming-of-Age
If the JSON file cannot be loaded or contains invalid data, an error message will appear.

Question 3:

Concepts Used:
•	jQuery library: Simplifies HTML element selection and manipulation.
•	CDN (Content Delivery Network): Loads jQuery from the official online source.
•	DOM manipulation: Changes HTML elements using jQuery.
•	.text(): Changes the text content of an element.
•	.addClass(): Adds a CSS class to an element.
•	.on("click", ...): Handles button click events.
•	CSS: Applies styling to the selected element.
•	Native JavaScript vs jQuery: Compares two ways to manipulate HTML elements and handle events.

How to Run:
•	Open Visual Studio Code.
•	Open your Lab4b project folder.
•	Open jquery-dom.html.
•	-Make sure the jQuery CDN link is included in the <head> section: https://code.jquery.com/jquery-4.0.0.min.js
•	Save the file.
•	Right-click inside the editor and select Open with Live Server.
•	Check that the text changes to Modified Text.
•	Check that the myDIV element has a coral background and 16px padding.
•	Click the Click me button.
•	Confirm that an alert displays Button clicked!.
Important: An internet connection is needed to load jQuery from the CDN.

Expected Result:
•	The original text changes to Modified Text.
•	The myDIV element receives the myStyle CSS class.
•	Clicking the button displays an alert message.

Screenshots:

Question 1:
<img width="679" height="575" alt="image" src="https://github.com/user-attachments/assets/a3a2097f-833c-41d8-b1ff-697d9dbffc51" />

Question 2:
<img width="595" height="432" alt="image" src="https://github.com/user-attachments/assets/30b4fa84-2113-4f08-ae42-5538a32c978e" />

Question 3:
<img width="505" height="314" alt="image" src="https://github.com/user-attachments/assets/e129428b-e807-4da7-b5cb-35c27ffc0fc0" />
