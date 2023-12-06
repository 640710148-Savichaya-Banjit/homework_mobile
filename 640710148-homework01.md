#### `homework 1 :640710148 สวิขญา บาลจิตร์ `
```dart
import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});
  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
        title: 'Flutter Demo',
        theme: ThemeData(
          colorScheme: ColorScheme.fromSeed(seedColor: Colors.deepPurple),
          useMaterial3: true,
        ),
        home: Scaffold(
            appBar: AppBar(
              title: Text('Savichaya Banjit'),
              centerTitle: true,
            ),
            body: Center(
              child: Text(
                'ชื่อ:สวิชญา บาลจิตร์ \nรหัสนักศึกษา:640710148',
                style: TextStyle(
                  fontSize: 24.0,
                  fontWeight: FontWeight.bold,
                  color: Colors.brown,
                ),
              ),
            )));
  }
}



```
