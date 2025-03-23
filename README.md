# Angular Electron Forge Boilerplate

![Angular](https://img.shields.io/badge/Angular-13-red?style=flat&logo=angular) ![Electron](https://img.shields.io/badge/Electron-25-blue?style=flat&logo=electron)

A boilerplate to quickly start an **Electron** project with **Angular**, using **Electron Forge** for packaging and distribution management.

![image](https://github.com/user-attachments/assets/c8fda3ac-8889-4a9d-9073-d2186208bae1)


## ✨ Features

- **Angular 13** integrated with **Electron 25**
- **Electron Forge** for simplified project management
- **TypeScript support** for both Angular and Electron
- **Optimized build** for production
- **Hot reload** for development

## 🚀 Installation and Start

### 1. Clone the repository
```sh
git clone https://github.com/and75/angular-electron-forge-boilerplate.git
cd angular-electron-forge-boilerplate
```

### 2. Install dependencies
```sh
npm install
```

### 3. Start in development mode
```sh
npm start
```

The application will launch with **hot reload** enabled.

### 4. Build for distribution
```sh
npm run make
```
The generated files will be found in the `out/` folder.

## 📁 Project Structure
```
angular-electron-forge-boilerplate/
├── src/
│   ├── app/          # Angular code
│   ├── assets/       # Static assets
│   ├── environments/ # Environment configurations
│   ├── main.ts       # Angular entry point
│
├── electron/
│   ├── main.ts       # Electron main process
│   ├── preload.ts    # Preload script for security
│
├── package.json      # Project configuration
├── forge.config.js   # Electron Forge configuration
```

## 🔐 Security

This project follows **Electron Security Guidelines**, limiting Node.js usage in the renderer process through a **preload script**.

## 📜 License

Distributed under the **MIT** license.

---
🔗 **GitHub Repository**: [Angular Electron Forge Boilerplate](https://github.com/and75/angular-electron-forge-boilerplate)

