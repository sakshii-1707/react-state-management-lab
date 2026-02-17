# 🚀 React State Management Lab

This repository contains implementations of state management techniques in React using:

- 🔹 React Context API
- 🔹 Redux Toolkit

These experiments were developed as part of Unit-4: State Management.

---

## 📌 Experiment 1: Global State Management using React Context API

### 🎯 Aim
To implement global state management in a Single Page Application using the React Context API.

### 🛠 Technologies Used
- React
- Vite
- Context API
- useContext Hook

### 💡 Features
- Theme toggle (Light / Dark)
- Global state without prop drilling
- Provider & Consumer implementation

### 📂 Folder
`context-api-app`

pictures to understand:
<img width="1899" height="969" alt="image" src="https://github.com/user-attachments/assets/4a4b5285-610a-465c-8e82-357ebe9a3587" />


## 📌 Experiment 2: State Management using Redux Toolkit (Counter Application)

### 🎯 Aim
To implement centralized state management using Redux in a React application.

### 🛠 Technologies Used
- React
- Redux Toolkit
- React-Redux
- Vite

### Concepts Covered

- createContext()
- Context Provider
- useContext()
- Redux Store
- createSlice()
- configureStore()
- useSelector()
- useDispatch()

### 💡 Features
- Increment counter
- Decrement counter
- Reset counter
- Centralized global store

### 📂 Project Folder
`redux-counter-app`\

pictures to understand:
<img width="1762" height="724" alt="image" src="https://github.com/user-attachments/assets/5d393724-11de-4d7a-a5e3-596cafb26b4c" />
<img width="1803" height="809" alt="image" src="https://github.com/user-attachments/assets/0bcd162d-e9f2-4538-ad4d-708ae91940ca" />



## 📊 Context API vs Redux

| Context API | Redux |
|-------------|--------|
| Suitable for small apps | Suitable for large-scale apps |
| Less setup | Structured architecture |
| Simple global state | Advanced state management |
| No middleware | Supports middleware |

## ▶ How to Run the Projects

### 1️⃣ Clone the repository

```bash
git clone https://github.com/sakshii-1707/react-state-management-lab.git

```
2️⃣ Navigate into a project
cd context-api-app

or

cd redux-counter-app
3️⃣ Install dependencies
npm install
4️⃣ Start development server
npm run dev
