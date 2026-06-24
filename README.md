# Inventaire Café — Application Mobile Android

Application de gestion de caisse et inventaire pour café, conçue pour Android (APK).

## Stack technique
- Android natif (Kotlin) + WebView
- HTML/CSS/JS embarqué dans l'APK (assets/)
- localStorage pour persistance locale
- Supabase pour sync cloud (import/export par utilisateur)

## Structure
```
app/
  src/main/
    assets/
      index.html        ← Application principale (tout-en-un)
    java/.../
      MainActivity.kt   ← WebView host
    res/
      layout/
        activity_main.xml
      values/
        strings.xml
  build.gradle
build.gradle
settings.gradle
```
