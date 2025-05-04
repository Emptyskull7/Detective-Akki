# 🕵️‍♂️ DevDetective

DevDetective is a simple and responsive web app that lets you search for any GitHub user's profile and see all their public details like name, bio, repos, followers, etc. It's built using pure HTML, CSS, and JavaScript — no frameworks, no libraries, just core web stuff.

---

## 🔗 Live Project

👉 https://dev-detective-akki.netlify.app/

---

## ✨ Features

- Search for any GitHub user
- See their profile picture, bio, username, location, repos, followers, following, and more
- Handles errors like "User not found" smoothly
- Toggle between light and dark mode
- Fully responsive — works great on both mobile and desktop
- Minimal and clean UI

---

## 🧠 What I Used

- **HTML** for the structure
- **CSS** for all styling and theming (used CSS variables for light/dark mode)
- **JavaScript** for everything dynamic – DOM updates, API calls, error handling, and theme toggling
- **GitHub API** to fetch user data (public API: `https://api.github.com/users/{username}`)

---

## 🛠 Folder Structure

DevDetective/
│
├── index.html // Main page structure
├── styles.css // Styles for light/dark mode and layout
├── script.js // JS code for logic and API calls
└── assets/ // (optional) screenshots or icons


---

## ⚙️ How It Works

- You type a GitHub username and hit search
- It makes a fetch request to the GitHub API
- If the user exists, their data shows up on the page
- If not, it displays an error message
- You can also toggle between dark and light themes — it updates instantly using CSS variables

---

## 📱 Screenshots

![image](https://github.com/user-attachments/assets/9daea20f-120a-4b7c-8ee1-1ea5c95b85e8)
![image](https://github.com/user-attachments/assets/74e806df-8465-4cd3-8db7-2b8b96b6cb35)
![image](https://github.com/user-attachments/assets/5eb373fb-5e0f-4c1b-aa2f-39b0a091ff2d)




Example:
- Light Mode preview  
- Dark Mode preview  
- Mobile view layout

---

## 🚀 Run It Locally

```bash
# Clone the repo
git clone https://github.com/Emptyskull7/Detective-Akki.git

# Go into the folder
cd DevDetective

# Just open index.html in your browser
