# Japanese Learning App

Mobile application designed to help learners efficiently study Japanese writing systems and vocabulary.

The goal of this project is to create a modern alternative to flashcard learning tools by combining spaced repetition, handwriting practice and automated vocabulary creation.

---

## Motivation

Learning Japanese often requires using multiple tools:
- flashcard apps (Anki, Quizlet)
- notebooks for writing practice
- vocabulary lists from textbooks

This project aims to combine these learning methods into a single mobile application.

---

## Main Features

### Flashcard Learning
- Study **hiragana, katakana and kanji** using flashcards
- Mark cards as **easy / difficult**
- Use this feedback to adapt the learning algorithm

### Level-based Learning
- Study kanji by difficulty levels
- Support for **JLPT levels (N5–N1)** and possibly **Kanken levels**

### Predefined Card Lists
The application will include built-in study lists such as:
- JLPT N5 kanji
- JLPT N4 kanji
- common vocabulary lists

These lists may be retrieved from an external **Japanese language API or dataset**.

### Custom Flashcard Lists
Users can create their own flashcard decks:
- vocabulary
- grammar
- kanji

---

### Photo-to-Flashcard Creation (Experimental Feature)

Users will be able to create flashcards from a **photo of handwritten notes**.

Example workflow:
1. Take a photo of a notebook page
2. Detect words and translations using OCR
3. Automatically generate flashcards

This feature aims to reduce the time required to manually create flashcards.

---

### Writing Practice

The app will include a **touch writing area** where users can practice writing:

- hiragana
- katakana
- kanji

This helps reinforce memorization through handwriting.

---

### User Accounts & Progress

- User accounts to save learning progress
- Tracking of studied cards
- Progress-based learning statistics

---

### Difficult Card Tracking

The application will maintain a **global list of difficult cards**, allowing users to review all cards they struggled with across all decks.

---

## Planned Technologies

Possible technologies for the project:

Mobile application:
- Java / Android

Backend (optional):
- API for card management
- database for user progress

Other technologies:
- OCR for text detection
- Japanese language datasets or APIs

---

## Project Status

Early development phase.

Current progress:
- application concept
- feature design
- interface prototypes
