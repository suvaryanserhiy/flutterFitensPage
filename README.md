# 🏋️ Fitness Nutrition App

A beautiful and modern Flutter application for exploring healthy recipes, diet recommendations, and nutrition information. Browse through various food categories, discover personalized diet plans, and find popular meal options to support your fitness journey.

## 📋 Table of Contents

- [🏋️ Fitness Nutrition App](#️-fitness-nutrition-app)
  - [📋 Table of Contents](#-table-of-contents)
  - [✨ Features](#-features)
  - [📸 Screenshots](#-screenshots)
  - [🚀 Getting Started](#-getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [📁 Project Structure](#-project-structure)
  - [📦 Dependencies](#-dependencies)
    - [Main Dependencies](#main-dependencies)
    - [Dev Dependencies](#dev-dependencies)
  - [💻 Usage](#-usage)
  - [🛠️ Development](#️-development)
    - [Running Tests](#running-tests)
    - [Code Analysis](#code-analysis)
    - [Building for Production](#building-for-production)
  - [🤝 Contributing](#-contributing)
  - [📄 License](#-license)
  - [🔗 Resources](#-resources)

## ✨ Features

- **Category Browsing**: Explore different food categories including Salad, Cake, Pie, and Smoothies
- **Diet Recommendations**: Get personalized diet recommendations with detailed information
- **Popular Diets**: Discover trending and popular diet plans
- **Search Functionality**: Search for specific recipes and meals
- **Modern UI**: Beautiful, clean interface with custom SVG icons
- **Responsive Design**: Optimized for various screen sizes
- **Custom Fonts**: Uses Poppins font family for a professional look

## 📸 Screenshots

_Add screenshots of your app here_

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (3.5.4 or higher)
- [Dart SDK](https://dart.dev/get-dart) (comes with Flutter)
- Android Studio / Xcode (for mobile development)
- VS Code or Android Studio (recommended IDEs)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/flutterFitensPage.git
   cd flutterFitensPage
   ```

2. **Install dependencies**

   ```bash
   flutter pub get
   ```

3. **Run the app**

   ```bash
   flutter run
   ```

   Or use your IDE's run button to launch the app on your preferred device/emulator.

## 📁 Project Structure

```
lib/
├── main.dart                 # App entry point
├── models/                   # Data models
│   ├── category_model.dart   # Category data model
│   ├── diet_model.dart       # Diet recommendation model
│   └── popular_model.dart    # Popular diets model
└── pages/                    # App pages/screens
    └── home.dart             # Home page with main UI

assets/
└── icons/                    # SVG icons for the app

fonts/                        # Custom Poppins font files
```

## 📦 Dependencies

### Main Dependencies

- **flutter**: The Flutter SDK
- **flutter_svg**: ^2.0.16 - For rendering SVG icons
- **cupertino_icons**: ^1.0.8 - iOS-style icons

### Dev Dependencies

- **flutter_test**: Testing framework
- **flutter_lints**: ^5.0.0 - Linting rules for code quality

For a complete list of dependencies, see [pubspec.yaml](pubspec.yaml).

## 💻 Usage

1. **Launch the app** - The home screen displays the main interface
2. **Browse Categories** - Scroll horizontally through different food categories
3. **View Recommendations** - Check out personalized diet recommendations
4. **Explore Popular Diets** - See trending diet plans with details
5. **Search** - Use the search bar to find specific recipes

## 🛠️ Development

### Running Tests

```bash
flutter test
```

### Code Analysis

```bash
flutter analyze
```

### Building for Production

**Android:**

```bash
flutter build apk --release
```

**iOS:**

```bash
flutter build ios --release
```

**Web:**

```bash
flutter build web
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🔗 Resources

- [Flutter Documentation](https://docs.flutter.dev/)
- [Dart Documentation](https://dart.dev/guides)
- [Flutter Cookbook](https://docs.flutter.dev/cookbook)
- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)

---

Made with ❤️ using Flutter
