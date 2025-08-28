# 🌙 Mood Tracker (Java CLI Application)

A simple **command-line Mood Tracker** written in Java.  
This program allows you to log your moods with optional notes, search past moods, edit existing entries, delete moods, and export them to a file.

---

## ✨ Features

- ➕ **Add Moods**  
  Record a mood with:
  - Current date & time  
  - Custom date & time  
  - Optional notes  

- 🔍 **Search Moods**  
  - By date (see all moods for that day)  
  - By specific mood entry (mood + date + time)  

- 📝 **Edit Moods**  
  Update notes for a specific mood entry.  

- ❌ **Delete Moods**  
  - Delete all moods on a specific date  
  - Delete one specific mood entry  

- 📂 **Export Moods**  
  Save all moods into a text file (`Moods.txt`).  

- 📋 **View All Moods**  
  List all saved moods directly in the console.  

---

## 🛠️ Tech Stack

- **Language:** Java (JDK 8+ recommended)  
- **Libraries:**  
  - `java.util` (ArrayList, Scanner)  
  - `java.time` (LocalDate, LocalTime, DateTimeFormatter)  
  - `java.io` (FileWriter, PrintWriter)  

---

## 📂 Project Structure

```text
mood-tracker/
├── Mood.java                 # Represents a mood entry (name, date, time, notes)
├── InvalidMoodException.java # Custom exception for invalid/duplicate moods
├── MoodTracker.java          # Main driver class with menu and logic
└── README.md                 # Project documentation
