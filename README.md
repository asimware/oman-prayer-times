# Contributing

If you want to contribute to this project, follow these steps to set up and run the source code on Windows.

## 1. Download the Source Code

Download and extract the project files to any folder on your computer.

---

## 2. Install Node.js

Install Node.js first (npm is included with it):

https://nodejs.org/

After installation, restart CMD if needed.

---

## 3. Open CMD in the Project Folder

Example:

```bash
cd path\to\project
```

---

## 4. Install Dependencies

Run:

```bash
npm install
```

This installs all required dependencies for the project.

---

## 5. Run the Application

To start the app directly without building the `.exe` file:

```bash
npm start
```

or

```bash
npm run start
```

---

## 6. Build the Windows Executable

To build the Windows `.exe` application:

```bash
npm run build:win
```

The generated build files will appear in the configured output/build directory.
