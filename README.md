# Javascript
A dynamic currency converter web application built with HTML5, CSS3, and Vanilla JavaScript. It leverages modern ES6+ features, asynchronous API fetching, and comprehensive DOM manipulation to provide real-time currency conversions and live country flag updates
# 💱 Currency Converter Web App

A clean, responsive, and fully interactive currency conversion tool that fetches live exchange rates and dynamically synchronizes country flags in real-time.

## 🚀 Key JavaScript Concepts & Features Implemented

This project serves as a practical implementation of modern Vanilla JavaScript concepts:

- **Asynchronous JavaScript (`async/await` & `fetch` API):** Handled asynchronous HTTP requests to fetch live exchange rate data from external endpoints without blocking the main thread, wrapped in `try...catch` blocks for robust error handling.
- **Advanced DOM Manipulation:** Dynamically created, selected, and modified HTML elements on the fly (`document.createElement`, `appendChild`, `querySelector`, and parent-element traversal) to build out currency dropdown options and update flag image sources.
- **Event-Driven Programming:** Utilized multiple event listeners (`change` for dropdown updates, `click` for conversion submission, and `load` for initial state rendering), alongside `event.preventDefault()` to manage default form behaviors.
- **Loops & Data Structures:** Iterated through complex objects and collections using `for...of` loops and `for...in` loops to dynamically populate currency codes and country mappings.
- **String & Number Manipulation:** Sanitized user inputs, handled case conversions (`toLowerCase()`), and formatted numerical output data cleanly using `.toFixed()`.

## 🛠️ Tech Stack
- **HTML5** – Semantic markup and form layout
- **CSS3** – Custom styling, layout design, and responsive containers
- **Vanilla JavaScript (ES6+)** – Core logic, API integration, and DOM control
- **APIs:** Open Exchange Rate API & Flags API
