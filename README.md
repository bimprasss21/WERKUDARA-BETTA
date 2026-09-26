# Werkudara Betta Android Project

Android WebView project for the Werkudara Betta shop app.

## Design
- Aquarium background with betta fish, bubbles, plants and rocks
- Blue glassmorphism panels
- Responsive layout for phone and wide screens
- Indonesian navigation: Ringkasan, Pembelian, Penjualan, Stok, Kematian, Biaya, Laporan

## Data
The HTML app keeps its database in WebView localStorage using the existing key:
`werkudara_betta_finance_v1`

The project does not overwrite existing localStorage data on normal app startup.

## Build
Open this folder in Android Studio, let Gradle sync, then Build > Build APK(s).
The APK will be generated under `app/build/outputs/apk/`.
