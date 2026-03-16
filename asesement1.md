

# Flutter Coding Assessment  Simple Notes App

## Time Limit

**1 hour (60 minutes)**

---

# Objective

Create a **simple Notes application** using Flutter where users can **add and delete notes**.

This assessment evaluates:

* Flutter fundamentals
* UI building
* Basic state management
* Code readability

---

# Requirements

## 1. Notes List Screen

Display a list of notes.

Each note should display:

* **Title**
* **Description**

Example:

```
Meeting Notes
Discuss project requirements

Shopping List
Milk, Bread, Eggs
```

Requirements:

* Use **ListView**
* If there are no notes, show a message:

```
No notes available
```

---

# 2. Add Note

Users should be able to add a new note.

Fields:

* Title (required)
* Description (optional)

UI suggestion:

* Two **TextFields**
* One **Add button**

Rules:

* Title cannot be empty
* After adding, the note should appear in the list

---

# 3. Delete Note

Users should be able to delete a note.

Options:

* Delete icon button
  or
* Swipe to delete

When deleted:

* The note should disappear from the list immediately.

---

# Technical Requirements

Use:

* **Flutter**
* **Null safety**
State management
---

# UI Requirements

The UI should include:

* **AppBar with title "Notes App"**
* Button or **FloatingActionButton** to add a note
* Clean layout

Example layout:

```
Notes App

[ Add Note ]

--------------------
Title: Meeting Notes
Description: Project discussion

Title: Shopping List
Description: Milk, Bread
```

---

# Code Expectations

We will evaluate:

* Proper Flutter widget usage
* Clean and readable code
* clean  structure
* Data Caching 



Suggested structure (optional):

```
lib/
 ├── main.dart
 ├── note_model.dart
 └── notes_screen.dart
```

---

# Bonus (Optional but prefered) 

* Show note creation time
* Edit note
* Better UI design
* Brainstorm
---
 
