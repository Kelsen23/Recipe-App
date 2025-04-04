# 🥗 Recipe Book App

A simple and clean Recipe Book application built with **React**, **TypeScript**, **Zustand** for state management, and **Tailwind CSS** for styling.

## 📸 Features

- ✅ Add new recipes
- ✏️ Edit existing recipes
- ❌ Delete recipes
- 🧠 Uses **Zustand** for global state
- 🎨 Styled with Tailwind CSS

## 🚀 Getting Started

### 1. Clone the repository

```
git clone https://github.com/Kelsen23/recipe-book.git
cd recipe-book
```

### 2. Install dependencies

```
npm install or yarn install
```

### 3. Run the app

```
npm run dev
```

```
yarn dev
```

## Project Structure

src/
├── components/
│   └── RecipeApp.tsx       # Main UI component with form and recipe list
├── store/
│   └── useStore.ts         # Zustand store
├── App.tsx                 # Renders the RecipeApp
└── main.tsx                # ReactDOM entry point

## Technologies Used

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Zustand](https://github.com/pmndrs/zustand)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/)

## Todo / Possible Improvements

🔄 Persist recipes using localStorage or a database
🔍 Search & filter functionality
🌙 Dark mode

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
