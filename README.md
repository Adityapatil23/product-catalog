# Product Catalog App

A modern Android application built with Kotlin Multiplatform Mobile (KMM) and Jetpack Compose, showcasing a product catalog with a clean architecture approach.

## Features

- Product list screen with modern Material 3 design
- Detailed product view with comprehensive information
- Error handling and retry functionality
- Loading states and indicators
- Responsive UI with smooth navigation
- Clean Architecture implementation
- Kotlin Multiplatform Mobile (KMM) setup

## Tech Stack

- **Language**: Kotlin
- **UI Framework**: Jetpack Compose
- **Architecture**: Clean Architecture / MVVM
- **API Client**: Ktor
- **State Management**: StateFlow
- **Dependency Injection**: Manual (can be extended with Koin)
- **Image Loading**: Coil
- **Testing**: Kotest, Mockk

## Project Structure

```
ProductCatalog/
├── shared/
│   ├── src/
│   │   ├── commonMain/
│   │   │   ├── data/
│   │   │   │   ├── api/
│   │   │   │   ├── model/
│   │   │   │   └── repository/
│   │   │   └── presentation/
│   │   │       ├── navigation/
│   │   │       ├── productlist/
│   │   │       └── productdetails/
│   │   └── test/
├── androidApp/
│   └── src/
│       └── main/
└── gradle/
```

## Setup Instructions

1. Clone the repository
2. Open the project in Android Studio
3. Sync the project with Gradle files
4. Run the app on an Android device or emulator

## Requirements

- Android Studio Arctic Fox or newer
- Minimum SDK: 24
- Target SDK: 34
- Kotlin version: 1.9.20
- Gradle version: 8.1.0

## API Integration

The app uses the DummyJSON API (https://dummyjson.com/docs/products) for product data.

## Testing

The project includes unit tests for the ViewModels and Repository layer. To run the tests:

1. Open the project in Android Studio
2. Navigate to the test directory
3. Right-click and select "Run Tests"

## Future Improvements

- Add image gallery/carousel for product images
- Implement offline caching
- Add search and filtering functionality
- Implement pagination for the product list
- Add more comprehensive error handling
- Implement UI tests
- Add animations for screen transitions
- Implement dark mode support
- Add product categories navigation

## License

This project is licensed under the MIT License - see the LICENSE file for details. 