# Calorie-Calculator

A mobile application built with Flutter that helps users track their food intake by simply taking a picture of their meal. The app estimates food volume, calories, and nutritional breakdown using computer vision and provides users with daily tracking features.

📱 Features

📸 Food recognition – Take a photo of your food and the app detects it

📊 Volume estimation – Calculates approximate food volume from images

🔥 Calorie calculation – Displays calories and macronutrients (carbs, protein, fats)

📅 Daily log – Keep track of meals and nutrition history

🎯 Custom goals – Set daily calorie targets

💾 Offline support – Save food entries locally (if implemented)

☁️ API Integration – Fetch nutritional data from a food database (if used)

🛠️ Tech Stack

Framework: Flutter

Language: Dart

Computer Vision:

TensorFlow Lite / PyTorch Mobile (if used for food recognition)

ARCore / CameraX (for depth & volume estimation)

Database/Storage:

Local: sqflite / hive

Cloud: Firebase / REST API (optional)

State Management: Provider / Riverpod / Bloc
