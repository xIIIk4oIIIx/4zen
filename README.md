# 🧘 4Zen (Cross-Platform Meditation App)

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-Cross_Platform-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Dart-Mobile_Dev-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/SQLite-Offline_First-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

Minimalistyczna, cross-platformowa (Android & iOS) aplikacja do medytacji i relaksacji. Wyróżnia się w pełni natywnym odczuciem, płynnymi animacjami oraz innowacyjnym systemem miksowania dźwięków otoczenia z główną ścieżką dźwiękową, działającym całkowicie offline.

## ✨ Główne funkcje

* **Podwójny Mikser Audio (Audio Mixer):** Możliwość jednoczesnego odtwarzania ścieżki głównej (np. z asystentem medytacji) oraz niezależnego kanału ambientowego (np. dźwięk deszczu, wiatru, ognia) z osobną regulacją głośności.
* **Architektura Offline-First:** Aplikacja skanuje i odtwarza lokalne pliki audio z urządzenia użytkownika, nie wymagając połączenia z internetem.
* **Mood Check-In & Analityka:** Moduł pozwalający na określenie nastroju przed sesją i zapisywanie historii postępów w lokalnej bazie danych.
* **Zarządzanie sesją:** Wbudowany wyłącznik czasowy (Sleep Timer) pozwalający na precyzyjne planowanie długości sesji medytacyjnych.
* **Nowoczesny UI/UX:** Interfejs zaprojektowany z dbałością o detale, wzbogacony o interaktywne, odprężające animacje Lottie.

## 🛠️ Architektura & Tech Stack

* **Flutter & Dart:** Jedna baza kodu kompilowana do natywnych aplikacji na systemy Android oraz iOS.
* **`just_audio` & `audio_service`:** Zaawansowane zarządzanie strumieniami audio, obsługa odtwarzania w tle oraz integracja z systemowymi powiadomieniami multimedialnymi na ekranie blokady.
* **`sqflite`:** Relacyjna baza danych działająca na urządzeniu, odpowiedzialna za przechowywanie historii odtworzeń, ulubionych utworów i statystyk nastroju.
* **Lottie:** Renderowanie zaawansowanych wektorowych animacji przy minimalnym obciążeniu procesora.

## 🚀 Uruchomienie lokalne

1. Upewnij się, że masz zainstalowane środowisko [Flutter SDK](https://flutter.dev/docs/get-started/install) oraz emulator Android/iOS (lub podłączone fizyczne urządzenie).
2. Sklonuj repozytorium:
   ```bash
   git clone [https://github.com/xIIIk4oIIIx/4zen.git](https://github.com/xIIIk4oIIIx/4zen.git)
3.  Przejdź do folderu z projektem i pobierz zależności:
    ```bash
    cd 4zen-app
    flutter pub get
    ```
4.  Uruchom aplikację:
    ```bash
    flutter run
    ```

## 📸 Zrzuty ekranu / UI Showcase

| Ekran Główny | Odtwarzacz | Mikser Audio (Ambient) |
|:---:|:---:|:---:|
| <img width="841" height="1280" alt="image" src="https://github.com/user-attachments/assets/23496702-f37c-4d5b-a7fb-5e0f70be1ad7" /> | <img width="841" height="1280" alt="image" src="https://github.com/user-attachments/assets/ab7385bf-6344-4047-adf6-7fd9326e4340" /> | <img width="841" height="1280" alt="image" src="https://github.com/user-attachments/assets/bc1d64f3-0fba-4d12-9cea-9b2ac58902d2" /> |
