# 📰 News App

![Kotlin](https://img.shields.io/badge/Kotlin-1.9.0-purple?style=for-the-badge&logo=kotlin)
![Android](https://img.shields.io/badge/Platform-Android-green?style=for-the-badge&logo=android)
![Architecture](https://img.shields.io/badge/Architecture-MVVM-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)

> 🚀 **Proudly developed during the internship at Technook** 

A state-of-the-art **News Application** crafted with modern Android development practices. This app delivers a premium user experience with real-time updates, offline caching, and a stunning "Glassmorphism" inspired UI.

## ✨ Key Features

### 🌟 Unique "Wow" Factors
- **🥇 Developer Badge**: A Gold Gradient Badge in the *About* screen recognizing the Technook Internship.
- **⏱️ Smart Reading Time**: AI-inspired logic calculating estimated reading time for every article.
- **🎨 Gradient Aesthetics**: A visual treat with Gold & Purple gradients.

### � Core Functionality
- **Top Headlines**: Breaking news from 100+ sources.
- **Categories**: Filter by Business, Tech, Health, and more.
- **Search**: Powerful search engine for topics of interest.
- **Offline Mode**: Save articles to Favourites (Room Database).
- **Immersive Reading**: Built-in WebView with sharing capabilities.

## 🏗️ Architecture

The app follows the **MVVM (Model-View-ViewModel)** pattern to ensure separation of concerns and testability.

```mermaid
graph TD
    UI[Fragments/Activities] --> ViewModel
    ViewModel --> Repository
    Repository --> Remote[Retrofit (NewsAPI)]
    Repository --> Local[Room DB (Caching)]
```

## 📸 Screenshots

| **Headlines** | **Search** | **Article** |
|:---:|:---:|:---:|
| <img src="https://via.placeholder.com/150" width="200"/> | <img src="https://via.placeholder.com/150" width="200"/> | <img src="https://via.placeholder.com/150" width="200"/> |

## 🚀 Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/Ajaykannagit/newsApp.git
    ```
2.  Open the project in **Android Studio**.
3.  Add your API Key in `local.properties`:
    ```properties
    apiKey=YOUR_NEWSAPI_KEY
    ```
4.  Build and Run.

## 🤝 Contribution
Contributions are welcome! Star the repo if you like it. ⭐

---
*Built with ❤️ by **Ajay kanna A***
