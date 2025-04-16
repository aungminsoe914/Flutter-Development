Here’s the updated README file with the "Developed by Aung Min Soe" credit included:

---

# Flutter runApp() Minimal Example

This Flutter project demonstrates the most basic use of the `runApp()` function with a simple `Center` widget displaying the text "Hello World" in a right-to-left text direction.

## Features

- **Minimal Setup**: Only uses the `Center` widget and the `Text` widget.
- **No Material Design**: Avoids the Material library for simplicity.
- **Right-to-Left Text Direction**: Demonstrates setting a specific text direction.

## Getting Started

### Prerequisites

Make sure Flutter is installed and configured on your system. Refer to the [Flutter installation guide](https://flutter.dev/docs/get-started/install) if needed.

### Installation

1. Clone this repository:
  
   ```

2. Retrieve dependencies (none are required for this minimal example):
   ```bash
   flutter pub get
   ```

### Running the App

Run the app on a simulator or a connected device using the following command:

```bash
flutter run
```

You should see a screen with the text "Hello World" centered on the screen, displayed in a right-to-left direction.

## Code Overview

### main.dart

```dart
import 'package:flutter/material.dart';

void main(){
  runApp(
    const Center(
      child: Text(
        "Hello World",
        textDirection: TextDirection.rtl,
      ),
    ),
  );
}
```

### Key Concepts

1. **`runApp()`**: Initializes the Flutter application and sets the `Center` widget as the root widget.
2. **`Center` Widget**: Centers its child widget within the available space.
3. **`Text` Widget**: Displays the string "Hello World".
4. **`TextDirection.rtl`**: Ensures the text is displayed from right to left.

## Customization

To add more functionality, you can replace the `Center` widget with more complex layouts or introduce Material Design elements like `Scaffold` or `AppBar`.

## Contributing

Feel free to fork this repository and submit a pull request with improvements or variations.


---

### Developed by Aung Min Soe
