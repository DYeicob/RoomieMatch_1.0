# 🏠 RoomieMatch

**RoomieMatch** is a web application designed to help people find their ideal flatmate. It allows users to create profiles, explore other users' profiles, manage room or apartment listings, send private messages, and leave reviews.

---

## 📋 Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## ✨ Features

- **User Authentication:** Sign up and log in system.
- **Profile Management:** Create and edit personal profiles (name, age, city, bio, budget, tags).
- **Advanced Search:** Find flatmates using tag filters and budget ranges.
- **Listing Management:** Publish and manage ads for rooms or apartments.
- **Favorites:** A "like" system to save favorite profiles.
- **Internal Messaging:** Secure communication between users to coordinate cohabitation.
- **Reviews & Ratings:** Review system for users to share their experiences with others.

---

## 🕹️ Demo

> The application can be run locally by opening `index.html` in a modern browser that supports ES modules.  
> **Note:** All data is stored in `localStorage` to simulate a database.

---

## ⚙️ Installation

1. **Clone the repository:**

```bash
git clone [https://github.com/your-username/roomiematch.git](https://github.com/your-username/roomiematch.git)

```

2. **Open the `index.html` file in your browser:**

> It is recommended to use browsers like Chrome, Edge, or Firefox to ensure compatibility with ES modules.

3. **Optional (Recommended):** For a more stable environment, serve the application using a local server (e.g., `Live Server` in VSCode) to avoid CORS issues with local ES modules.

---

## 📁 Project Structure

```text
RoomieMatch/
│
├─ index.html           # Main application file (HTML/Scripts)
├─ style.css            # Global styles
├─ logo.png             # Application logo
├─ profile1.png, ...    # Sample profile images
├─ listing1.png, ...    # Sample listing images
├─ icon-*.png           # UI icons
└─ README.md            # Project documentation

```

> **Note:** All scripts are integrated within `index.html` to simplify local module loading.

---

## 🛠️ Technologies Used

* **HTML5 & CSS3**: Structure and styling.
* **JavaScript (ES6+)**: Logic and DOM manipulation.
* **[Lit-HTML](https://lit.dev/)**: Dynamic template rendering.
* **LocalStorage**: Client-side data storage simulating a persistent database.

---

## 🚀 Usage

1. Open the application in your browser.
2. Create an account or log in with an existing user.
3. Browse available profiles or apartment listings.
4. Apply search filters based on your preferences.
5. "Like" profiles that interest you to save them.
6. Send messages to other users to coordinate logistics.
7. Publish and manage your own housing ads.
8. Write reviews for users you have lived with previously.

---

## 🤝 Contributing

If you wish to contribute to RoomieMatch:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/new-functionality`).
3. Make your changes and commit them.
4. Submit a pull request describing your improvements or fixes.

---

## 📜 License

This project is licensed under the **MIT License**.
See the [LICENSE](https://www.google.com/search?q=LICENSE) file for more information.
