Hi there! 
Flutter expert with 6+ years in the field. Led teams building mobile apps and libraries using Flutter since its early days. Skilled at guiding developers to create high-quality Flutter projects.
🌱 What I'm currently learning
👨🏾‍💻 Currently diving into content creation - whipping up YouTube videos and Teachable courses on Flutter. Always excited to share knowledge and learn new tricks in the Flutter ecosystem. What's next? Whatever cool tech catches my eye! 🚀


⚡ “The more I learn, the more I realize how much I don't know.” ― Albert Einstein
I'm available to speak at events or join panel discussions to share technical knowledge. Feel free to reach out if you need a Flutter expert for your conference or meetup.
🔥 Recent Talks and Workshops
Flutter & AI Fusion: Powering Apps with Intelligence
Debug Like a Pro: Harnessing the Power of Dart DevTools in Flutter
Flutter Go Router In Depth
Flutter Workshop: Consuming APIs like an Expert
Git For Kids
Flutter Workshop: Mastering Flutter BLoC

# Simple News App - Flutter Clean Architecture with BLOC, Freezed, Get_It Package

This repository contains a simple news app built using Flutter, following the Clean Architecture principles and utilizing BLOC pattern along with Freezed and Get_It packages.

## Description

The Simple News App is a mobile application that displays news articles fetched from an API. It demonstrates the implementation of Clean Architecture in Flutter, separating the app into layers with clear responsibilities. The architecture allows for easy testing, maintenance, and scalability.

The app uses the BLOC (Business Logic Component) pattern to manage the state of the application. BLOC separates the business logic from the UI, making the code more modular and testable. It also utilizes the Freezed package to generate immutable classes for state management and data models. The Get_It package is used for dependency injection, making it easier to manage dependencies between different layers of the app.

## Features

- Display a list of news articles fetched from an API.
- Cached Thumbnail with Fallback and Loading Placeholder

## Screenshots
<img src="https://github.com/mimamch/news_app_clean_architecture/blob/main/screenshot1.png" width="100">


## Structure

The app follows the Clean Architecture principles, with the following structure:

- `lib/`
  - `core/`: Contains Core Utilities that used entire application
  - `features/`:
    - `app`: Initializes the app and sets up the dependency injection.
    - `{features_a}`:
        - `data/`: Contains the data layer responsible for handling data fetching and caching.
        - `domain/`: Defines the core business logic and entities of the app.
        - `presentation/`: Contains the UI layer of the app, including BLOCs, views, and widgets.
  - `main.dart`: Entry point of the application.

## Dependencies

The app utilizes several Flutter packages:

- [flutter_bloc](https://pub.dev/packages/flutter_bloc): Implements the BLOC pattern for state management.
- [freezed](https://pub.dev/packages/freezed): Generates immutable classes for state management and data models.
- [json_annotation](https://pub.dev/packages/json_annotation): Provides annotations for JSON serialization.
- [json_serializable](https://pub.dev/packages/json_serializable): Generates code for JSON serialization based on annotations.
- [get_it](https://pub.dev/packages/get_it): Provides dependency injection capabilities.
- [dio](https://pub.dev/packages/dio): Handles HTTP requests to fetch news articles.
- [equatable](https://pub.dev/packages/equatable): Simplifies equality comparisons for state management.

For a complete list of dependencies, please refer to the `pubspec.yaml` file.

## Contributing

Contributions to the Simple News App are welcome! If you find any bugs or would like to suggest improvements, please open an issue or submit a pull request.

When contributing, please follow the existing code style and ensure that all tests pass before submitting any changes. Additionally, make sure to update the documentation if necessary.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code according to your needs.



