# RecyclerView--Kotlin
# Android Homework 4: RecyclerView

## Overview

This Android project, part of the CIS600 course, focuses on implementing a RecyclerView to display movie data with various functionalities. The homework includes tasks related to UI enhancements and RecyclerView operations.

## Table of Contents

1. [Front-page Activity](#front-page-activity)
2. [RecyclerView Implementation (Task 1)](#recyclerview-implementation-task-1)

## Front-page Activity

### Description

The front-page activity is reused from the previous homework. It loads a front-page fragment with buttons for "About Me" and "Task 1." Clicking these buttons navigates to the corresponding fragments or activities.

## RecyclerView Implementation (Task 1)

### Description

Implemented a RecyclerView to display movie data. Each row of the RecyclerView contains the movie image, title, description, rating, and a CheckBox. Three buttons above the RecyclerView provide functionalities such as selecting all items, clearing all selections, and deleting selected movies. Additional features include toggling CheckBox status, duplicating items on long press, and loading a Fragment with movie details on click.

### Functionality Highlights

1. **Get the RecyclerView to work:** Each row is implemented as a CardView.

2. **CheckBox Interaction:** Clicking the CheckBox toggles its status. Clicking the row does not toggle the CheckBox.

3. **Select All / Clear All:** Buttons for selecting all and clearing all CheckBoxes.

4. **Delete Selected Movies:** Deleting selected movies with animation effects.

5. **Duplicate on Long Press:** Long-pressing an item duplicates and adds it below the current item with animation effects.

6. **Load Fragment on Click:** Clicking on a list item loads a Fragment displaying details of the selected movie on a phone.

7. **Orientation Handling:** Selected movies persist when the phone's orientation changes.

8. **Tablet Layout:** On tablets, the movie list and selected movie are displayed side by side.

9. **Different Layouts based on Rating:** Movies with a rating of 8.0 and above have a different layout than those below 8.0.

10. **Item Animation:** Implemented an item animation using the wasabeef library.

### Usage

Clone the repository and open the project in Android Studio to explore and run the RecyclerView implementation.

