organizacao_novo_mundo/
├── lib/
│   ├── main.dart
│   ├── screens/
│   │   ├── auth/
│   │   │   ├── login_screen.dart
│   │   │   └── register_screen.dart
│   │   └── home/
│   │       └── home_screen.dart
├── pubspec.yaml
└── README.md
name: organizacao_novo_mundo
description: Aplicativo para gestão de congregação - Organização do Novo Mundo

publish_to: 'none'
version: 1.0.0+1

environment:
  sdk: '>=3.0.0 <4.0.0'

dependencies:
  flutter:
    sdk: flutter
  firebase_core: ^2.24.0
  firebase_auth: ^4.18.0
  cloud_firestore: ^4.15.0
  google_maps_flutter: ^2.5.4
  http: ^0.16.2
  geolocator: ^11.2.2
  hive: ^2.2.3
  hive_flutter: ^1.1.0
  path_provider: ^2.1.2
  flutter_local_notifications: ^15.1.1
  firebase_messaging: ^14.7.3
  pdf: ^3.10.4
  printing: ^5.12.2
  share_plus: ^7.2.2

dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_launcher_icons: ^0.13.1
  build_runner: ^2.4.6

flutter:
  uses-material-design: true
  assets:
    - assets/images/
    
