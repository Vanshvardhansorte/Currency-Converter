# Currency Converter

A simple Flutter app that converts an amount in US dollars (USD) to Indian rupees (INR). The app includes a Material interface and an alternate Cupertino interface.

> **Note:** The conversion currently uses a fixed rate of **1 USD = 81 INR**. It does not retrieve live exchange rates.

## Features

- Enter a USD amount and convert it to INR.
- Display the converted amount to two decimal places.
- Material Design interface, used when the app launches.
- An alternate Cupertino interface is also included in the source.

## Requirements

- Flutter SDK with Dart SDK `>=3.4.3 <4.0.0`
- A supported device or platform toolchain:
  - **Windows desktop:** Visual Studio 2022 Build Tools or Visual Studio with the **Desktop development with C++** workload, including the MSVC C++ build tools, CMake tools, and a Windows SDK.
  - **Web:** Chrome or another supported browser.
  - **Android/iOS:** The relevant platform SDK and tooling configured in Flutter.

See the [Flutter installation guide](https://docs.flutter.dev/get-started/install) for setup instructions.

## Run the app

From the project directory, download the Dart and Flutter packages:

```shell
flutter pub get
```

Run on Windows desktop:

```shell
flutter run -d windows
```

Run in Chrome:

```shell
flutter run -d chrome
```

You can also select another connected device with `flutter devices` and run the app using its device ID.

## Project structure

- `lib/main.dart` — application entry point; launches the Material interface.
- `lib/pages/currency_converter_material_page.dart` — Material currency converter screen.
- `lib/pages/currency_converter_cupertino_page.dart` — alternate Cupertino currency converter screen.
- `test/` — Flutter widget tests.

## Development checks

Run static analysis and the Flutter tests with:

```shell
flutter analyze
flutter test
```
