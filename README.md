# 📱 Basic Calculator – Jetpack Compose

A clean, modern, and fully functional calculator app built using **Jetpack Compose** and **Kotlin**, following the **MVVM architecture pattern**.
This project was developed as a **practice app** to explore **state management**, **unidirectional data flow**, and **declarative UI design** in Android.

---

## 🚀 Features

* **Basic arithmetic operations**: Addition, subtraction, multiplication, division
* **Clear (AC)** and **Delete (DEL)** functionality
* **Decimal number support**
* **Dynamic state updates** using `mutableStateOf`
* **Responsive & modern UI** with Jetpack Compose layouts (`Row`, `Column`, `Box`)
* **MVVM Architecture**:

  * **ViewModel** for logic & state handling
  * **Composable functions** for UI
* **Custom button grid layout** with spacing, color themes, and rounded shapes

---

## 🛠️ Tech Stack

* **Language**: Kotlin
* **UI Toolkit**: Jetpack Compose
* **Architecture**: MVVM (Model-View-ViewModel)
* **State Management**: `mutableStateOf` + unidirectional data flow
* **IDE**: Android Studio

---

## 📂 Project Structure

```
com.kshitiz.basiccalculator
│
├── MainActivity.kt               # Entry point, sets up theme & content
├── Calculator.kt                  # Main calculator UI grid
├── CalculatorButton.kt            # Reusable button composable
│
├── CalculatorAction.kt            # Defines possible user actions
├── CalculatorState.kt             # Holds current state (numbers, operation)
├── CalculatorOperation.kt         # Supported arithmetic operations
├── CalculatorViewModel.kt         # Business logic & state updates
│
└── ui.theme/                      # Theme, colors, and typography
```

---

## ⚙️ How It Works

1. **User Interaction**

   * Each button click triggers a corresponding `CalculatorAction`.
2. **ViewModel Processing**

   * The `CalculatorViewModel` processes the action, updates the `CalculatorState`, and applies calculation logic.
3. **UI Update**

   * The Composables automatically recompose when state changes, instantly reflecting the updated result.

---

## 🖥️ How to Run

1. Clone the project to your local machine.
2. Open it in **Android Studio**.
3. Let Gradle sync and build the project.
4. Run on an emulator or a physical Android device.

---

If you want, I can also **make this README more recruiter-focused** with a short “Why I built this” section so it feels more personal and compelling on your resume and GitHub. That way it doesn’t just look like any calculator project, but a deliberate showcase of your **Jetpack Compose skills**.

Do you want me to add that?

