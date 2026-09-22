Game Vault

A responsive web application that fetches, searches, and displays video game metadata in real-time using the **RAWG Video Game API**.


How the App Works
- **Initial Data Fetch:** Sends an HTTP `GET` request to the RAWG API on page load to retrieve top video games.
- **Interactive Search:** Queries the RAWG search endpoint dynamically when users search by game title.
- **Dynamic Card UI:** Injects game posters, titles, user ratings, and release dates into a responsive HTML grid.

How to Run It Locally

1. **Clone the Repository:**
   git clone [https://github.com/Jann-Arpon/Arpon_VideoGames.git](https://github.com/Jann-Arpon/Arpon_VideoGames.git)
2. **Navigate into the directory**
3. **Create the Configuration File**
   Create a file named `config.js` in the root directory and add your RAWG API key
    type const RAWG_API_KEY = "YOUR_RAWG_API_KEY_HERE";
4. **Then launch the application**
   Open `index.html` directly in any browser or launch it using VS Code's Live Server extension.
