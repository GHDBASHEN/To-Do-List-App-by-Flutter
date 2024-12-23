# To-Do List App

A simple and elegant To-Do List application built with Flutter to help you manage your daily tasks efficiently.
![image](https://github.com/user-attachments/assets/f3489d04-f673-4940-80fa-e34da8bfd832)


## Features

- Add, edit, and delete tasks
- Mark tasks as completed
- Beautiful and user-friendly UI
- Responsive design for all screen sizes

## Requirements

- Flutter SDK 3.6.0 or later
- Dart SDK
- Visual Studio (for Windows builds)
- Android Studio or an Android Emulator (for Android builds)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/ghdbashen/todo_list_app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd todo_list_app
   ```

3. Install dependencies:
   ```bash
   flutter pub get
   ```

4. Run the app:
   ```bash
   flutter run
   ```

## Folder Structure

```plaintext
.
├── assets/
│   ├── fonts/
│   │   ├── Schyler-Regular.ttf
│   │   ├── Schyler-Italic.ttf
│   │   ├── TrajanPro.ttf
│   │   └── TrajanPro_Bold.ttf
│   ├── images/
│   │   └── task_icon.png
├── lib/
│   ├── main.dart
│   ├── models/
│   ├── screens/
│   └── widgets/
├── pubspec.yaml
└── README.md
```

## How to Use

1. Launch the app on your desired platform (Android, iOS, or Windows).
2. Add a new task by tapping the "+" button.
3. Edit or delete tasks by selecting them.
4. Mark tasks as completed by checking the checkbox.

## Troubleshooting

- **Asset Not Found Errors:** Ensure the font and image files are correctly placed in the `assets/` folder and paths match those defined in `pubspec.yaml`.
- **Build Errors:** Run `flutter clean` and rebuild the app.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your feature description"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, feel free to reach out at your-email@example.com.
