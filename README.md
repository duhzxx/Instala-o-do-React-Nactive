# 📱 Como criar um projeto com React Native - Com e Sem Expo

Este repositório ensina como criar um projeto **React Native** de duas formas:
1. Com Expo
2. Sem Expo (React Native CLI)

---

## 🚀 1. Pré-requisitos

Independente da abordagem, você precisa:

- Node.js (LTS recomendado) → [Baixar aqui](https://nodejs.org/)
- Editor de código (VS Code recomendado) → [Baixar aqui](https://code.visualstudio.com/)

Para Sem Expo:
- Java JDK → [Baixar aqui](https://www.oracle.com/java/technologies/javase-downloads.html)
- Android Studio → [Baixar aqui](https://developer.android.com/studio)
- CocoaPods (macOS para iOS) → `sudo gem install cocoapods`

Para Com Expo:
- App Expo Go no celular (Android/iOS)

---

## 📦 2. Criando Projeto Com Expo

### Passo 1 - Criar projeto
```bash
npx create-expo-app NomeDoProjeto
cd NomeDoProjeto
```

### Passo 2 - Rodar no celular (Expo Go)
```bash
npx expo start
```
- Escaneie o QR Code no terminal ou navegador usando o app Expo Go.

### Passo 3 - Rodar no emulador
- Android: `npx expo start --android`
- iOS (macOS): `npx expo start --ios`

---

## 📦 3. Criando Projeto Sem Expo (React Native CLI)

### Passo 1 - Instalar CLI
```bash
npm install -g react-native-cli
```

### Passo 2 - Criar projeto
```bash
npx react-native init NomeDoProjeto
cd NomeDoProjeto
```

### Passo 3 - Rodar no Android
```bash
npx react-native run-android
```

### Passo 4 - Rodar no iOS (macOS)
```bash
npx pod-install ios
npx react-native run-ios
```

---
