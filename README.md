# Drawing App

A Flutter-based drawing application that allows users to create and save digital artwork. The app provides an intuitive interface for drawing with various tools and features.

<img src="https://user-images.githubusercontent.com/12158468/185896735-2046411e-d47c-4e3c-96fb-cb4c82f6bec1.gif" width="375" height="650"/>

## Features

- 🎨 Free-hand drawing with customizable brush
- ✏️ Drawing tools including pencil and eraser
- 💾 Save drawings to device gallery
- 🎯 Custom pointer support for better precision
- 📱 Responsive design for various screen sizes

## Getting Started

### Prerequisites

- Flutter SDK (>=2.17.6)
- Dart SDK (>=2.17.6)
- Android Studio / VS Code with Flutter extensions

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/drawing_app.git
```

2. Navigate to the project directory:
```bash
cd drawing_app
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the app:
```bash
flutter run
```

## Dependencies

- `provider: ^6.0.3` - For state management
- `flutter_svg: ^1.0.3` - SVG rendering support
- `path_provider: ^2.0.11` - File system access
- `gallery_saver: ^2.3.2` - Save drawings to gallery

## Project Structure

```
drawing_app/
├── assets/
│   ├── images/
│   │   ├── eraser.svg
│   │   └── pencil.svg
│   └── pointers/
│       └── pencil_pointer.svg
├── lib/
└── ...
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
