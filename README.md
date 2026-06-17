# Real-Time Search UI

A beautiful, responsive, and dynamic real-time user search interface built with HTML, CSS, and Vanilla JavaScript. 

## ✨ Features

- **Real-Time Filtering**: Instantly filters through user profiles as you type in the search bar.
- **Glassmorphism Design**: Features a premium frosted-glass effect for the user cards using modern CSS `backdrop-filter` techniques.
- **Responsive Layout**: Seamlessly adapts to different screen sizes and device types.
- **Interactive Elements**: Includes smooth hover animations and transition effects for an engaging user experience.
- **Empty State Handling**: Automatically displays a "No Users found" message when a search yields no results.

## 🛠️ Technologies Used

- **HTML5**: For the structural layout of the application.
- **CSS3 / Tailwind CSS**: Custom styling with Vanilla CSS for the intricate glassmorphism cards and hover effects, combined with Tailwind CSS (via CDN) for rapid layout structure and responsiveness.
- **Vanilla JavaScript (ES6)**: For DOM manipulation, event listening, and the core search filtering logic.

## 🚀 Getting Started

To run this project locally, you don't need any complex build tools. 

1. Clone the repository:
   ```bash
   git clone https://github.com/Gurkaran18/Real-Time-Search.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Real-Time-Search
   ```
3. Open `index.html` in your favorite web browser. 
   *(Alternatively, you can use the VS Code "Live Server" extension for a better development experience).*

## 💡 How It Works

- The user data is stored as an array of objects within `script.js`.
- An `input` event listener is attached to the search bar.
- On every keystroke, the JavaScript `.filter()` method creates a new array of users whose names match the search input (case-insensitive).
- The DOM is then cleared and re-rendered with only the matching user cards. If no matches are found, an appropriate fallback message is displayed.
