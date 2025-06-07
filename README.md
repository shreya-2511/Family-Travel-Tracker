# 🌍 Family Travel Tracker


## ✨ Features

* Allows each family member to create their own profile.
* Users can select and add countries they’ve visited.
* The visited countries are highlighted on a world map.
* Each user’s map is shown in a custom color theme.
* Tracks and displays the total number of countries visited.

---

## 🧠 What I Learned
Building the Family Travel Tracker helped me practice:
* Creating a Node.js and Express backend
* Using EJS for dynamic page rendering
* Working with PostgreSQL and writing SQL queries
* Managing relational data between users and countries

---

## 🛠 Technologies Used

* **Frontend**: HTML5, CSS3, EJS
* **Backend**: Node.js, Express.js
* **Database**: PostgreSQL with the `pg` module
* **Tools**: body-parser, pgAdmin, Map SVG (for world map rendering)

---

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/shreya-2511/Family-Travel-Tracker.git
   cd Family-Travel-Tracker
   ```

2. **Install dependencies**

   ```bash
   npm i
   npm i ejs express pg
   ```

3. **Set up the PostgreSQL database**

   * Create a `world` database with the following tables:

     * `users(id, name, color)`
     * `countries(country_name, country_code)`
     * `visited_countries(user_id, country_code)`
   * Optionally, seed with a few users and countries.

4. **Run the app locally**

   ```bash
   node index.js
   ```

5. **Visit the app**
   Open `http://localhost:3000` in your browser.

---
