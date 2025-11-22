# Recipe App (Flutter)

A beautiful **Recipe App** built with **Flutter** using **TheMealDB API**.  
This app allows users to explore recipes by category, view meal details including ingredients and instructions, and enjoy a professional and clean UI.

---

## 📱 Features

- Display recipe **categories** in a horizontal scroll
- List meals under each category
- Show **meal details** with:
  - Image
  - Category & Area
  - Ingredients list
  - Instructions
- Pull-to-refresh for latest data
- Responsive and modern UI with shadows, rounded corners, and Google Fonts

> **Note:** YouTube button has been removed to avoid launch issues.

---

## 🛠️ Tech Stack

- **Flutter** for UI
- **Dart** for programming
- **HTTP package** for REST API requests
- **Google Fonts** for professional typography
- **TheMealDB API** as the data source

---

## 🌐 API

- [TheMealDB](https://www.themealdb.com/api.php)  
- Public REST API for recipes
- Endpoints used:
  - `categories.php` – fetch all categories
  - `filter.php?c=` – fetch meals by category
  - `lookup.php?i=` – fetch meal details
  - `search.php?s=` – search meals by name
  - `random.php` – get random meal

---

## 📂 Project Structure

lib/
│
├─ models/
│ └─ meal.dart
│
├─ screens/
│ ├─ home_screen.dart
│ ├─ category_meals_screen.dart
│ └─ meal_detail_screen.dart
│
├─ services/
│ └─ api_service.dart
│
└─ main.dart

## Install dependencies

flutter pub get


## Run the app

flutter run

## 🔗 References

TheMealDB API
Flutter Documentation
HTTP Package
Google Fonts Package
