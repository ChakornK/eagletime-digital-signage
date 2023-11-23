# Eagletime Digital Signage

## 📃 Prerequisites

Instructions for Windows

### Rust

```
winget install --id Rustlang.Rustup
```

### Visual Studio C++ Build Tools

Install Visual Studio 2022 with the `Desktop Development with C++` workload. Make sure that `MSVC C++` and `Windows 10 SDK` are selected under `Installation details`

### Node.js

```
winget install OpenJS.NodeJS
```

## 🚀 Running from source

First, install node modules by running

```
npm install
```

Start the app by running

```
npm start
```

## 📦 Publishing

Build the app into an executable by running

```
npm run build
```

The generated app installer can be found in `./src-tauri/target/release/bundle`
