
# My First React Native App 🚀

Welcome to my first hands-on journey with **React Native**, built using **Expo**, **Expo Router**, and **Zustand** for global state. This app is structured with stack, tab, and modal navigation.

## 📦 Tech Stack

- **React Native** (with Expo SDK)
- **Expo Router** – file-based navigation
- **Zustand** – global state management
- **Async Storage** (coming soon)
- **Atomic Design Pattern** (coming soon)

## 📱 Features

- 🧭 **Multi-layer Navigation**  
  - Tabs (bottom navigation)
  - Stacks (within tabs)
  - Modals (presented on top)

- 🧠 **Global State with Zustand**  
  Shared message logic across screens

- 📂 **Clean File Structure**  
  Organized using `(tabs)/`, `(stack)/`, `(modals)/`

## 📁 Directory Structure

```
app/
├── (tabs)/             # Tab screens
│   ├── index.tsx       # Home screen
│   └── details.tsx
├── (stack)/            # Stack screens
│   └── profile.tsx
├── (modals)/           # Modal screens
│   ├── _layout.tsx
│   └── modal.tsx
├── _layout.tsx         # Root layout
├── store/              # Zustand global state
│   └── messageStore.ts
```

## 🏁 Getting Started

```bash
npm install
npx expo start
```

Scan the QR code with **Expo Go** or use an emulator/web view.

## ✅ Progress

| Day | Module                         | Status |
|-----|--------------------------------|--------|
| 1   | Initial setup & navigation     | ✅ Done |
| 2   | State interaction & buttons    | ✅ Done |
| 3   | Modal screen & routing cleanup | ✅ Done |
| 4   | Zustand global state           | ✅ In Progress |

## 🧠 Author

Built by **Abraham Bortey Danfa**  
Front-End Dev & Designer  
🇬🇭 Ghana

---

## 🧭 Next Steps

- [ ] Async Storage
- [ ] API Mocking & Fetching
- [ ] Atomic Design refactor
- [ ] Theme toggle
