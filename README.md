# trying_flutter

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Creating a flutter app

<img width="1274" height="1014" alt="Screenshot 2026-03-03 114200" src="https://github.com/user-attachments/assets/b5956f1b-1494-4f92-8ae1-641a6675d651" />

```
import 'package:flutter/material.dart';

void main() => runApp(MaterialApp(
  home: Text('hey ninjas:'),
)); //MaterialApp
```

 <img width="1919" height="1079" alt="Screenshot 2026-03-03 114213" src="https://github.com/user-attachments/assets/966ef735-546b-4153-a98e-362cf5e42f58" />

## Scaffold widget

<img width="1276" height="1021" alt="Screenshot 2026-03-03 115040" src="https://github.com/user-attachments/assets/3af75e24-471c-49e5-98d6-ad8f6ce6e077" />

```
import 'package:flutter/material.dart';

void main() => runApp(MaterialApp(
  home: Scaffold(
    appBar: AppBar(
      title: Text('my first app'),
      centerTitle: true,
    ), //AppBar
    body: Center(
      child: Text('hello ninjas:'),
    ), //Center
    floatingActionButton: FloatingActionButton(
    child: Text('click'),
    ), //FloatingActionButton
  ), //Scaffold
)); //MaterialApp
```

<img width="1297" height="994" alt="Screenshot 2026-03-03 115054" src="https://github.com/user-attachments/assets/60820997-906a-44fd-bf9a-8b9a14094124" />

## Colours & Font

<img width="1276" height="1079" alt="Screenshot 2026-03-03 122227" src="https://github.com/user-attachments/assets/d6090fde-8fbe-4864-94b1-208edb34ec0a" />

```
import 'dart:ui';
import 'package:flutter/material.dart';

void main() => runApp(MaterialApp(
  home: Scaffold(
    appBar : AppBar(
      backgroundColor: Colors.amber,
      title: const Text('Hallo 123'),
    ),
  body: Center(
    child: Text(
      'Henshin',
      style: TextStyle(
        fontSize: 30,
      fontWeight: FontWeight.bold,
        letterSpacing: 3,
        color: Colors.blueAccent,
      ),
      ),
),
  floatingActionButton: FloatingActionButton(
    onPressed: () {
        print('Button clicked');
      },
      child: const Icon(Icons.add),
      backgroundColor: Colors.amber,
    ),
  ),
));
```

<img width="1304" height="993" alt="Screenshot 2026-03-03 122238" src="https://github.com/user-attachments/assets/e9870e11-68d6-4af7-a445-2b79a5dfee50" />
