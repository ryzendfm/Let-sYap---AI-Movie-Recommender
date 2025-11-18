# 🎬 Let'sYap - AI Movie Recommender

Let'sYap is a beautiful, conversational AI chatbot designed to help you find the perfect movie. Instead of endless scrolling, have a simple "yap" with an AI that learns your taste and provides personalized recommendations.
* here's the live preview link : https://lets-yap.vercel.app/

## ✨ Features

* **Conversational Interface**: A sleek, chat-based UI for a natural and engaging user experience.
* **Dynamic Questions**: The AI generates unique questions to understand your movie preferences.
* **Smart Suggestions**: Get a curated list of 5 movie suggestions, complete with posters, ratings, and one-liners.
* **Detailed Movie Info**: Ask about any movie (new or suggested) to get a full detail card, including:
  * Backdrop and poster art
  * Plot overview
  * Rating, release year, and runtime
  * Director and top-billed cast
* **Instant Trailer Modal**: Watch movie trailers directly within the app, powered by YouTube.
* **Elegant UI/UX**: Features a stunning background, custom fonts, a "thinking" spinner, and a custom cursor for desktop.

## 🛠️ Tech Stack

* **Frontend**: HTML5, Tailwind CSS
* **Logic**: Vanilla JavaScript (ES6 Modules)
* **APIs**:
  * **Google Gemini API**: Powers the conversational AI, dynamic question generation, intent analysis, and movie title extraction.
  * **TMDB API**: Used to fetch all movie details, posters, backdrops, cast information, and trailers.
* **Libraries**:
  * **marked.js**: For rendering the AI's Markdown responses in the chat.

## 🚀 Getting Started

This project is contained in a single `index.html` file, making it incredibly simple to run.

### 1. Clone or Download

* Download the `index.html` file from this repository.

### 2. Get Your API Keys

* **Gemini API Key**: Go to [Google AI Studio](https://makersuite.google.com/app/apikey) to generate your free API key.
* **TMDB API Key**: Create a free account on [The Movie Database (TMDB)](https://www.themoviedb.org/settings/api) and generate a v3 API Key.

### 3. Add Your Keys to the File

* Open the `index.html` file in a text editor.
* Find lines 332-333 (or search for `GEMINI_API_KEY` and `TMDB_API_KEY`).
* Replace the placeholder strings with your actual API keys:

```javascript
// ... inside the <script type="module"> tag ...

const GEMINI_API_KEY = "YOUR_GEMINI_API_KEY_HERE";
const TMDB_API_KEY = "YOUR_TMDB_API_KEY_HERE";

// ... rest of the script ...
```

### 4. Run the App

* Simply open the `index.html` file in any modern web browser (like Chrome, Firefox, or Safari).

## 💬 How to Use

1. **Start the Conversation**: Type "hi" or ask for a movie (e.g., "suggest a good sci-fi movie" or "tell me about The Matrix").
2. **Get Details**: If you ask about a specific movie, its detail card will appear.
3. **Answer Questions**: If you ask for a suggestion, the AI will ask you 5 dynamic questions to learn your taste.
4. **Get Recommendations**: After you answer, a horizontal carousel of 5 movie recommendations will appear.
5. **Explore**: Click on a movie poster or "Watch Trailer" to learn more. You can continue chatting to ask about other movies.

## 📝 Credits

Developed with ❤️ by **Ryz. (Sooriyaa)**

---

Enjoy finding your next favorite movie! 🍿
