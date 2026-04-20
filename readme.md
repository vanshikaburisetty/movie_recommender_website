# 🎬 Movie Mood Recommender

An AI-based movie recommendation system that suggests movies based on your **mood, energy level, and preferences**.

---

## 🚀 Features

* 🎯 Mood-based movie recommendations
* 🌍 Multi-language support (English, Telugu, Hindi)
* ❤️ Add / Remove favorites
* 👤 User profile with editable details
* 🎬 Real movie posters using TMDB API
* ⚡ Fast and responsive UI
* 🔍 Personalized filtering (feeling, energy, goal, language)

---

## 🛠 Tech Stack

### Frontend

* React (Vite)
* JavaScript
* CSS

### Backend

* Flask (Python)
* Pandas
* Scikit-learn

### APIs

* TMDB (The Movie Database API)

---
## 📸 Screenshots
<img width="632" height="525" alt="WhatsApp Image 2026-04-20 at 4 05 21 PM" src="https://github.com/user-attachments/assets/3bbe42c6-310b-4a19-9acb-097131ec1970" />
<img width="1567" height="959" alt="WhatsApp Image 2026-04-20 at 4 05 21 PM (1)" src="https://github.com/user-attachments/assets/e391a9ca-2488-4f3c-9175-4b8d8f6d405f" />
<img width="1567" height="959" alt="WhatsApp Image 2026-04-20 at 4 05 21 PM (1)" src="https://github.com/user-attachments/assets/28d4f043-c03f-437b-8cc6-7bc1d015fe55" />
<img width="1530" height="928" alt="WhatsApp Image 2026-04-20 at 4 05 21 PM (2)" src="https://github.com/user-attachments/assets/f34be8b7-c16e-4b61-9ceb-a01bb1794c3c" />




## 📂 Project Structure

```text
movie-mode-recommender/
│
├── backend/
│   ├── app.py
│   ├── recommender.py
│   └── data/
│
├── frontend/
│   ├── src/
│   ├── components/
│   └── pages/
│
└── README.md
```

---

## ⚙️ Setup Instructions

### 🔹 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/movie-mode-recommender.git
cd movie-mode-recommender
```

---

### 🔹 2. Backend Setup

```bash
cd backend
pip install -r requirements.txt
python app.py
```

Server runs on:

```
http://127.0.0.1:5000
```

---

### 🔹 3. Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

## 🔐 Environment Variables

Create a `.env` file inside `frontend/`:

```env
VITE_TMDB_API_KEY=your_api_key_here
```

👉 Get API key from: https://www.themoviedb.org/

---

## ❤️ How It Works

1. User selects:

   * Feeling (Happy, Sad, Angry)
   * Energy level
   * Goal (Feel good, Emotional, Thriller, Horror)
   * Language

2. Backend processes input → detects mood

3. Movies are filtered from dataset

4. Frontend displays:

   * Movie list
   * Posters (via TMDB)
   * Favorite toggle ❤️

---




### 🏠 Home Page

![Home](screenshots/home.png)

### 🎯 Recommendation Results

![Recommendations](screenshots/recommendations.png)

### ❤️ Favorites Section

![Favorites](screenshots/favorites.png)

### 👤 User Profile

![Profile](screenshots/profile.png)

---

## 🚀 Future Improvements

* 🔐 Authentication (Firebase / JWT)
* 🎥 Trailer preview on hover
* ⭐ Ratings & reviews
* 📱 Mobile responsive UI
* 🌐 Deployment (Vercel + Render)

---

## 🤝 Contributing

Feel free to fork this project and submit pull requests!

---

## 📌 Author

**Burisetty Vanshika**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
