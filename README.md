# Flutter Namer App

A simple yet elegant Flutter application that generates random word pairs and allows users to save their favorites. This app demonstrates fundamental Flutter concepts including state management, responsive design, and animations.

## Features

- **Random Word Pair Generation**: Creates unique word combinations using the English language
- **Favorite Management**: Save and delete your favorite word pairs
- **History Tracking**: View previously generated word pairs with an animated history list
- **Responsive Design**: 
  - Mobile layout with bottom navigation
  - Tablet/Desktop layout with side navigation rail
  - Adaptive layout changes based on screen width
- **Material Design 3**: Modern UI following the latest Material Design guidelines
- **Smooth Animations**:
  - Page transitions
  - List item insertions
  - Card size changes
  - Gradient masking effects
- **State Management**: Uses Provider package for efficient state management across the app
- **Accessibility**: Includes semantic labels for better screen reader support

## Screenshots

*[Screenshots to be added]*

## Getting Started

### Prerequisites

- Flutter SDK (version 3.8.0 or higher)
- Dart SDK (compatible with your Flutter version)
- An IDE (VS Code, Android Studio, etc.)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/nag2mani/namer_app.git
   cd flutter_namer_app
   ```

2. Install the dependencies:
   ```bash
   flutter pub get
   ```

3. Run the app:
   ```bash
   flutter run
   ```

## Dependencies

- **flutter**: The Flutter SDK
- **english_words**: Provides random English word pairs
- **provider**: State management solution

## Architecture

The app follows a simple architecture:

- **main.dart**: Entry point of the application containing all UI widgets
- **MyApp**: Root widget that sets up the theme and providers
- **MyAppState**: Central state management class using ChangeNotifier
- **MyHomePage**: Main layout with responsive design handling
- **GeneratorPage**: Shows random word pairs and history
- **FavoritesPage**: Displays and manages favorite word pairs
- **HistoryListView**: Animated list showing previously generated word pairs

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Flutter team for creating such an amazing framework
- The authors of the english_words package
