# Computing-Aptitude-Project-report
“Mini Project Report on Library Recommendation &amp; Smart Traffic Light Systems (C++)”
# 📚 Library Recommendation System

A **console-based C++ application** that simulates an intelligent book suggestion engine for a library.  
It provides **personalized book recommendations** based on a user's reading preferences and history — mimicking real-world digital library systems.

---

## 🧩 Project Overview

The **Library Recommendation System** allows users to:
- Specify their favorite genres (e.g., *Fantasy, Sci-Fi, Thriller*).
- Indicate which books they have already read.
- Receive curated book suggestions that match their interests but exclude already-read titles.

---

## 🎯 Objectives

- Build a simple **digital recommendation tool** for libraries.
- Improve user engagement with tailored reading suggestions.
- Practice **C++ programming concepts** such as structures, vectors, maps, sets, and algorithmic filtering.

---

## ⚙️ Functional Overview

| Feature | Description |
|----------|-------------|
| **Data Organization** | Stores books in a structured map with unique IDs, titles, authors, and genres. |
| **User Input** | Collects user's name, preferred genres, and reading history. |
| **Recommendation Logic** | Filters and recommends books based on preferences and exclusions. |
| **Result Output** | Displays personalized recommendations in a clean format. |

---

## 🧠 Core Components

### **Data Structures**
- `struct Book` — Stores book details (`id`, `title`, `author`, `genre`).
- `struct User` — Stores username, preferred genres, and previously read book IDs.

### **Key Functions**
| Function | Purpose |
|-----------|----------|
| `loadBookDatabase()` | Initializes the built-in library catalog. |
| `getUserPreferences()` | Collects genres of interest from the user. |
| `getUserHistory()` | Records which books the user has already read. |
| `getRecommendations()` | Generates a recommendation list based on preferences and history. |
| `printRecommendations()` | Displays personalized recommendations. |

---

## 💻 How It Works

1. The program welcomes the user and asks for their name.  
2. The user selects preferred genres (e.g., *Fantasy*, *Sci-Fi*).  
3. The system displays all available books.  
4. The user enters the IDs of books they have already read.  
5. Based on this data, a personalized recommendation list is displayed.  

---
