# 🌤️ Weather App

A responsive and interactive **Weather App** built using **HTML, CSS, and JavaScript** that allows users to search for a city and view its current weather information.

🔗 **Repository:** https://github.com/Atibayounus/weather-app.git

---

## 📌 About the Project

The **Weather App** is a frontend web application designed to provide weather information through a simple and user-friendly interface.

Users can enter a city name and retrieve weather data, making it a practical project for learning how frontend applications communicate with external APIs.

This project focuses on combining **HTML, CSS, JavaScript, API integration, asynchronous programming, and DOM manipulation** into a functional web application.

---

## ✨ Features

* 🌍 Search weather by city
* 🌡️ Display current temperature
* ☁️ Show weather conditions
* 💧 Display humidity information
* 💨 Display wind information
* 🔎 Search-based weather updates
* ⚡ Dynamic data rendering
* ❌ Error handling for invalid searches
* 📱 Responsive interface
* 🎨 Clean and simple UI
* 🌐 API-based weather data

---

## 🛠️ Technologies Used

### 🌐 HTML5

Used to create the structure of the application.

HTML provides:

* Search input
* Search button
* Weather information container
* Weather details
* Page layout

---

### 🎨 CSS3

CSS is used to create the visual design of the application.

It handles:

* Layout
* Colors
* Typography
* Spacing
* Cards
* Buttons
* Responsive design
* Transitions
* Visual effects

---

### ⚡ JavaScript

JavaScript provides the main functionality of the application.

It handles:

* User input
* Search events
* API requests
* Fetching weather data
* Processing JSON responses
* DOM manipulation
* Dynamic content
* Error handling

---

## 🌦️ How It Works

The basic flow of the application is:

```text
Enter City
    ↓
Click Search
    ↓
JavaScript Gets City Name
    ↓
Send API Request
    ↓
Receive Weather Data
    ↓
Process Response
    ↓
Update the UI
    ↓
Display Weather Information
```

---

## 🔌 API Integration

The application uses a weather API to retrieve current weather information.

JavaScript can communicate with the API using the **Fetch API**:

```javascript
fetch(apiUrl)
    .then(response => response.json())
    .then(data => {
        // Update weather information
    })
    .catch(error => {
        // Handle error
    });
```

This demonstrates how a frontend application can retrieve and display data from an external service.

---

## 🧠 Core Concepts Practiced

This project provides practical experience with:

* JavaScript variables
* Functions
* Events
* DOM manipulation
* `fetch()`
* Promises
* JSON
* `async/await`
* API requests
* Error handling
* Conditional rendering
* User input
* Responsive design

---

## 📂 Project Structure

```text
weather-app/
│
├── index.html
├── style.css
├── script.js
│
├── images/
│
└── README.md
```

> The exact structure may vary depending on the files currently included in the repository.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Atibayounus/weather-app.git
```

### 2. Navigate to the Project

```bash
cd weather-app
```

### 3. Open the Application

Open:

```text
index.html
```

in a modern web browser.

For development, you can use **Live Server** in VS Code.

---

## 🔑 API Configuration

If the weather service requires an API key, create/configure your API key according to the API provider's instructions.

For example:

```javascript
const API_KEY = "YOUR_API_KEY";
```

> Never upload a private API key to a public GitHub repository. Use environment variables or another secure configuration method when appropriate.

---

## 📱 Responsive Design

The application is designed to work across different devices:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile
* 📲 Tablet

Responsive CSS helps keep the weather interface usable on different screen sizes.

---

## ❌ Error Handling

The application handles common situations such as:

* Invalid city names
* Empty search input
* API request failures
* Unavailable weather data
* Network errors

Providing feedback to the user makes the application more reliable and easier to use.

---

## 🎯 Project Goals

The main goals of this project are:

* Learn how APIs work
* Practice JavaScript `fetch()`
* Understand asynchronous programming
* Work with JSON data
* Manipulate the DOM dynamically
* Build a practical frontend application
* Improve responsive web design
* Practice error handling

---

## 🎓 Learning Outcomes

Through this project, I practiced:

* HTML5
* CSS3
* JavaScript
* DOM manipulation
* API integration
* Fetch API
* JSON
* Async programming
* Error handling
* Responsive UI development
* Git & GitHub

---

## 🔮 Future Improvements

Possible future features include:

* 📍 Detect weather using current location
* 📅 Multi-day weather forecast
* 🌡️ Celsius/Fahrenheit switch
* 🌙 Dynamic weather-based themes
* 🌅 Sunrise and sunset information
* 🌬️ More detailed weather statistics
* ⭐ Favorite cities
* 🕒 Recent searches
* 🎨 Improved animations
* 📱 Enhanced mobile UI

---

## 🌐 Live Demo

If the project is deployed, add the live website here:

🔗 **Live Demo:** `Add your deployed URL here`

---

## 👨‍💻 Author

**Atiba Dar**

🎓 Computer Science Student
🏫 University of Gujrat, Pakistan
💻 Frontend Developer & Programming Learner

### GitHub

🔗 [@Atibayounus](https://github.com/Atibayounus)

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

> **"Turn data into useful experiences. 🌦️💻"**
