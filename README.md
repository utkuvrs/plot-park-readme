<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/WRg6Pcd.png" alt="Project logo"></a>
</p>

<h3 align="center">Plot Park</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()

</div>

---

<p align="center"> Plot Park is Flutter mobile application project with iOS and Android operating systems in mind. Has the following features and more:
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>

Plot Park is a mobile application made with Flutter to park, track your vehicles. Plot Park also allows creating parking areas and managing existing parking areas through the mobile application.

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

## Architecture <a name = "architecture"></a>

| Layer                         | Component                 |
| ----------------------------- | ------------------------- |
| Presentation (UI Layer)       | auth_screen.dart          |
| Presentation (UI Layer)       | plot_rules_dialog.dart    |
| Business (State Management)   | auth_service.dart         |
| Business (Service Layer)      | auth_cubit.dart           |
| Persistence (Data Layer)      | auth_endpoint.dart        |
| Database/API (Infrastructure) | MsSQL, Firebase, REST API |

### Prerequisites

What things you need to install the software and how to install them.

## Flutter Version

```bash
Flutter 3.29.2 • channel stable • https://github.com/flutter/flutter.git
Framework • revision c236373904 (3 months ago) • 2025-03-13 16:17:06 -0400
Engine • revision 18b71d647a
Tools • Dart 3.7.2 • DevTools 2.42.3
```

Follow the steps on:

```html
https://docs.flutter.dev/get-started/install
```

### Setting Up The Environment

```

1. Set up your .env using the variables inside the .env.example

Make sure you are using a secure SSH key.

```

## 🔧 Running the tests <a name = "tests"></a>

There are two types of tests for Plot Park,

1. Automated tests that doesn't require an emulator to be tested (marked with _filename_\_test.dart)
2. Automated tests that require an emulator to be tested (marked with _filename_\_notest.dart)

### Break down into end to end tests

```bash
flutter test
```

### Coding Style

Dart is a very simple and straight forward programming language inspired by TypeScript and C.

[Effective Dart: Style](https://dart.dev/effective-dart/style)

Understanding Flutter's Widgets and how they are shown to the UI might be a little confusing but with practice it'll fit in.

[Flutter](https://docs.flutter.dev/get-started/learn-flutter)

## 💻 Usage <a name="usage"></a>

### 🧂 Flavor

```dart
  /// Developer Environment
  FlavorConfig(
    name: "DEV",
    color: AppColors.red,
    location: BannerLocation.topStart,
    variables: {
      "apiUrl": "https://example.api.com/",
      "locale": "en_US",
    },
  );
  /// Production Environment
  FlavorConfig(
    variables: {
      "apiUrl": "https://example.api.com/",
      "locale": "da_DK",
    },
  );
```

## ✍️ Authors <a name = "authors"></a>

- [@utkuvrs](https://github.com/utkuvrs)
