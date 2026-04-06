# Guess It! — Android Kotlin M3

**STEP IT Academy** — Android Mobile Application Development (Kotlin + XML UI)

> Module 3 — Architecture: ViewModel · LiveData · Data Binding

---

## About

Guess It is a word-guessing game. Hold the device in landscape, facing away from you.
Your friends give you clues — press **Got It** if you guess correctly, **Skip** to pass.
The game runs for 60 seconds, then shows your final score.

---

## Architecture

- **Pattern:** MVVM (Model-View-ViewModel)
- **UI:** Single Activity + 3 Fragments (Navigation Component)
- **State:** LiveData + ViewModel
- **Binding:** DataBinding (`@{}` expressions)
- **Navigation:** SafeArgs for type-safe argument passing

---

## Tech Stack

| Library | Version |
|---|---|
| Android Gradle Plugin | 9.0.1 |
| Navigation Component | 2.9.7 |
| Lifecycle (ViewModel + LiveData) | 2.9.0 |
| Min SDK | 24 |
| Target SDK | 36 |

---

## Screens

| Screen | Description |
|---|---|
| `TitleFragment` | Start screen |
| `GameFragment` | 60-second countdown gameplay |
| `ScoreFragment` | Final score display |

---

## Exercise Steps

| Step | Topic |
|---|---|
| Step 01 | Create the GameViewModel |
| Step 02 | Populate the GameViewModel |
| Step 03 | Add LiveData to GameViewModel |
| Step 04 | Add LiveData Encapsulation |
| Step 05 | Add End Game Event |
| Step 06 | Add the Timer |
| Step 07 | Add a ViewModelFactory |
| Step 08 | Add ViewModel to Data Binding |
| Step 09 | Add LiveData Data Binding |
| Step 10 | Map Transformation |
| Step 11 | (Optional) Add Buzzing |

---

## Course Info

- **Instructor:** Magn
- **Organization:** [chamkartechcambodia-sudo](https://github.com/chamkartechcambodia-sudo)
- **Course:** Android Kotlin — Batch 1
