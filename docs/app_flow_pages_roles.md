# **🗺️ App Flow, Pages & Roles: Voice-Activated Reading List App**

This technical document outlines the full application flow, page structure, and user role logic for the MVP version of the app. It is designed for development and UI/UX reference.

---

## **👥 User Roles**

* **User (default)**: All users have the same capabilities in the MVP.

* No admin panel or moderation functions are planned at this stage.

---

## **🔁 Overall App Flow (MVP)**

1. **Onboarding**

   * User opens app for the first time

   * Chooses basic personalization (e.g., "What kind of reader are you?")

   * Enters email to create profile or logs in (OAuth or passwordless email)

   * App sets user preferences in memory/database

2. **Voice Entry**

   * User taps mic icon (or says activation command)

   * Speaks a book-related phrase

   * App transcribes voice using Google STT

   * Transcription is passed to GPT-4 to extract metadata

   * App confirms: "Did you mean this book by \[Author\]?"

   * User confirms (voice or tap)

   * Entry is saved and user gets response: "Added to your reading list\!"

3. **Reading List Management**

   * User accesses visual list

   * Can filter, search, or sort entries

   * Can tag or prioritize entries

   * Can group entries by category, topic, or source

4. **Reminders / Recall**

   * User asks app (via voice or text): "What did I save from the podcast last week?"

   * App returns entries matching query context

   * Option to set reminder for later or reorder list

5. **User Settings & Personalization**

   * Update reading preferences (e.g., parenting, professional, hobby)

   * Control reminders, voice interaction tone, and responses

   * Export or back up reading list

---

## **📱 Page/Screen Structure**

### **1\. Welcome / Onboarding Page**

* User selects type of reader (optional)

* Light personalization: genres, goals, themes

* Email entry or login with minimal fields

### **2\. Home (Voice Capture)**

* Central mic button (large, inviting)

* Option to manually enter book text

* Small recent activity or shortcut section (e.g., "Saved 2 mins ago")

### **3\. Reading List Page**

* Visual list of all saved books

* Filter/sort controls (genre, author, priority, saved date)

* Search bar with auto-suggestions

* Tap book to view/edit details

### **4\. Book Detail Page**

* Book metadata: title, author, genre, source

* User notes / custom tags

* Buttons: prioritize, delete, set reminder, export

### **5\. Contextual Recall Page (Voice-Only or Hybrid)**

* Voice query results displayed visually

* Follow-up prompts: "Do you want to group these?"

* Option to create a list from context ("Podcast: Tim Ferriss")

### **6\. Reminders & Notifications Page**

* Upcoming reminder entries

* Manage notification timing or priority

* Voice activation: "Remind me about that book next week"

### **7\. Settings Page**

* Profile info (email, reader type)

* Preferences: genres, voice tone, interaction style

* Export tools

---

## **🔄 Transitions & Navigation**

* **Main Navigation**: Bottom tab bar (Home, Reading List, Reminders, Settings)

* **Voice-Only Mode**: Can access major functions without visual screen

* **Quick Access**: Floating mic or swipe-up voice command bar

* **Back navigation**: Standard back icon or gesture

---

## **✅ Final Notes**

* No need for admin, team roles, or user segmentation at MVP

* All users are equal and own their own data

* Everything is voice-optional but optimized for voice-first experience

Let me know if you'd like wireframes or clickable prototypes next\!

