# 🛠️ Implementation Plan & Scope

## 📦 Project Summary
Build a voice-first reading list app that helps users capture book recommendations on the go. Focus on fast execution of a clean MVP using voice input, GPT, and Supabase-backed storage.

---

## 🪜 Phased Development Plan

### ✅ Phase 1: MVP Build
**Goal:** Core voice-to-reading-list workflow
- [x] Mic button for voice input
- [x] Transcription using Web Speech API
- [x] Send transcript to GPT-4 via OpenAI API
- [x] Extract title, author, tags, and source
- [x] Save results in Supabase, scoped to user
- [x] Display basic list with search/filter
- [x] Visual confirmation (“Did you mean…”)

### 🔁 Phase 2: Personalization & Structure
**Goal:** Add features for power users and long-term use
- [ ] Book cover display via Open Library / Google Books API
- [ ] Add subject, notes, and priority metadata fields
- [ ] User onboarding flow with reader type selector
- [ ] Add backend structure for feature gating (premium-ready)
- [ ] Enable voice confirmation (“Yes, that’s it”)
- [ ] Add contextual recall prompts (“What did I save last week from Tim Ferriss?”)

### 💸 Phase 3: Monetization
**Goal:** Enable sustainable revenue streams
- [ ] Add affiliate links (Amazon, Booktopia, etc.)
- [ ] Enable subscription tier and gating
- [ ] Export list and sharing features
- [ ] AI-generated summaries or reading bundles

---

## ⚙️ Notes
- MVP must be voice-first, clean UI, and distraction-friendly
- Supabase used from day 1 (auth + DB)
- PWA structure prioritized over native for MVP
