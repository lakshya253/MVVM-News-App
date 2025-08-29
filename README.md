# 📰 MVVM News App (not-completed yet)

A modern **News Application** built using the [NewsAPI.org](https://newsapi.org/) and **Android MVVM architecture**.
The app provides real-time news from around the world, with smooth UI, offline support, and clean code practices.

---

## ✨ Features

* 📡 Fetches latest news from **NewsAPI.org**
* 🏗️ Built with **MVVM Architecture** (ViewModel, LiveData, Room, Repository)
* 🗄️ **Room Database** for offline storage & caching
* 🔍 Search news articles by keywords
* 💾 Save & manage favorite articles
* 🌙 Material Design with responsive UI

---

## 🛠️ Tech Stack

* **Kotlin**
* **Retrofit** – API calls
* **Gson** – JSON parsing
* **Room Database** – Local storage
* **Coroutines** – Background threading
* **LiveData & ViewModel** – Reactive UI updates
* **Navigation Component** – In-app navigation
* **Glide** – Image loading

---

## 🚀 Getting Started

### Prerequisites

* Android Studio (latest version recommended)
* A free [NewsAPI.org API key](https://newsapi.org/)

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/MVVMNewsApp.git
   cd MVVMNewsApp
   ```

2. Open the project in **Android Studio**

3. Add your API key inside:

   ```kotlin
   const val API_KEY = "your_api_key_here"
   ```

   (You can put this in `Constants.kt` or `local.properties` for better security.)

4. Run the app on an emulator or a physical device 🎉
   
---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

⚡ Built with ❤️ using MVVM, Kotlin & NewsAPI
