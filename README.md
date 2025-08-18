# Sorting Algorithm Dynamic Web Project

## Project Overview

This project is a front-end website designed to demonstrate the principles and implementations of various common sorting algorithms. It also provides an interactive quiz to test users' understanding of these algorithms. Through this website, users can browse the following content:

- Demonstration pages for various sorting algorithms (Bubble Sort, Counting Sort, Heap Sort, Insertion Sort, Merge Sort, Quick Sort, Radix Sort, Selection Sort).
- A main page that offers a brief introduction and links to the sorting algorithms.
- A login page to store and display user information (via localStorage).
- A random quiz page that allows users to test their knowledge of sorting algorithms, with a score and feedback displayed on the results page.
- An additional demonstration page that shows a simple implementation and flowchart for checking if a string is a Palindrome.

## Key Features

- **Sorting Algorithm Demonstrations**: Includes dynamic demonstrations of Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, Quick Sort, Heap Sort, Counting Sort, and Radix Sort.
- **Interactive Quiz**: The random quiz page (`randomTest.html`) provides multiple-choice questions, and the results page (`result.html`) displays the user's score and feedback for each question.
- **User Login**: A simple login page (`login.html`) allows users to enter a username and password, with the information stored in `localStorage` for use on other pages.
- **Additional Demo**: The `web1.html` page demonstrates palindrome checking with pseudocode, a flowchart, and related explanations for learning purposes.

## Directory Structure

```
sapt36-dynamicweb_sorting_algorithm/
└── Dynamic Web Final Project/
    ├── BubbleSort.html         // Bubble Sort demo, showing sorting process and time complexity (O(n²))
    ├── CountingSort.html       // Counting Sort demo, introducing its basic concepts and C language implementation
    ├── HeapSort.html           // Heap Sort demo, showing how to achieve O(nlogn) efficiency using a heap structure
    ├── InsertionSort.html      // Insertion Sort demo, explaining its principles and time complexity (O(n²))
    ├── MergeSort.html          // Merge Sort demo, sorting via a divide-and-conquer strategy, with O(nlogn) time complexity
    ├── QuickSort.html          // Quick Sort demo, introducing pivot and partitioning strategies, with an average time complexity of O(nlogn)
    ├── RadixSort.html          // Radix Sort demo, sorting sequentially by digit, showing its time complexity and implementation details
    ├── SelectionSort.html      // Selection Sort demo, demonstrating the process of sequentially selecting the smallest (or largest) element to sort
    ├── list.html               // Main page, providing an overview and navigation links to all sorting algorithms
    ├── login.html              // Login page where users can input username and password, storing info in localStorage
    ├── randomTest.html         // Random quiz page with multiple-choice questions related to sorting algorithms
    ├── result.html             // Quiz results page, displaying the user's score and feedback
    └── web1.html               // Additional demo page: Palindrome check with pseudocode, flowchart, and introduction

```

## How to Use

1. **Download or Clone the Project Files**
    - Download the entire `sapt36-dynamicweb_sorting_algorithm` directory to your local computer.
    - Website link: https://sapt.neocities.org/
2. **Open the Website**
    - You can directly open `login.html` with your browser as the home page to browse the demonstration pages for each sorting algorithm.
    - Alternatively, you can run the website using a local server (e.g., VS Code's Live Server extension) for a better interactive experience.
3. **User Login and Quiz**
    - Click on `login.html` and enter your username and password (data will be stored in `localStorage`).
    - After logging in, you can go to `randomTest.html` to take the sorting algorithm quiz, and view your score and feedback on `result.html`.
4. **Additional Features**
    - Click on `web1.html` to browse the "Palindrome Check" demonstration, which includes pseudocode, a flowchart, and explanations for learning purposes.

## Technologies and Resources

- **Front-end Technologies**: HTML5, CSS3, JavaScript
- **External Frameworks and Libraries**:
    - [Bootstrap 4.5.2](https://getbootstrap.com/): For quickly building responsive web pages and optimizing visual effects.
    - [jQuery 3.5.1](https://jquery.com/): To simplify DOM manipulation and event handling.
    - [Popper.js](https://popper.js.org/): To support Bootstrap components like tooltips.
- **Data Storage**: Uses HTML5's `localStorage` to access user login information and quiz results.

## Customization and Expansion

- **Layout and Styles**
Using the Bootstrap framework and some custom CSS, you can modify the styles or adjust the page structure as needed.
- **Functionality Expansion**
If you need to demonstrate other sorting algorithms, you can create a new page and add a link in `list.html`; to expand the quiz question bank, you can modify the JavaScript code in `randomTest.html` and `result.html`.
- **Interactive Features**
The login and quiz functions are implemented using JavaScript and `localStorage`, allowing users to modify the logic and interface design based on their needs.

## Notes

- **Browser Compatibility**
It is recommended to use a modern browser (e.g., Chrome, Firefox, Edge) for the best viewing experience.
- **External Resource Dependency**
The website relies on Bootstrap, jQuery, and Popper.js from CDNs. Unstable network connections may affect the display of certain components.
- **Data Privacy**
Login information is stored only on the user's local device and is not sent to the server. It is used for front-end demonstration purposes only.

**Project Author**
- Andrew Chen
