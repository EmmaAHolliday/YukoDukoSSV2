# 📘 Masterplan: Voice-Activated Reading List App

## ✨ Overview & Objectives
This app helps users capture and organize book recommendations they hear in everyday life—especially while listening to podcasts or multitasking—using only their voice. GPT-4 extracts structured book data from the voice transcript, building a personalized, categorized, and searchable reading list over time.

---

## 🎯 Target Audience
- Avid readers, lifelong learners, and podcast listeners
- People who often hear book recommendations in the moment but forget them later
- Users with busy hands or minds—parents, commuters, hobbyists
- Knowledge collectors who want long-term organization and personalization

---

## 🧩 Core Features (Phases)

### ✅ Phase 1 – Core MVP
- Voice input via mic button
- Transcription via Web Speech API (upgrade to Google Cloud later)
- GPT-4 integration to extract book metadata: title, author, tags, source
- Save per user (Supabase auth + DB)
- Reading list UI (basic display + filtering)
- Visual confirmation interface (“Did you mean…” with buttons)

### 🔁 Phase 2 – Enhanced Functionality
- Book cover image display via Open Library or Google Books API
- Additional metadata: subject, notes, priority
- Onboarding customization: define user reading types (e.g., parenting, fiction)
- Context-based memory: “Remind me about the book I heard last week”
- Voice-based confirmation options
- Backend-ready structure for user tiers (free vs. premium)
- Voice commands for sorting/filtering list (by genre, tag, etc.)

### 💸 Phase 3+ – Monetization & Personal Libraries
- Affiliate links (Amazon, Booktopia, etc.)
- Premium tier: auto-categorization, summary previews, export features
- Subscription infrastructure for scalable monetization
- Gifting or sharing reading lists
- Analytics dashboard for heavy users

---

## ⚙️ Technical Stack (High-Level)
- Frontend: Web app, built mobile-first, PWA compatible
- Backend: Supabase (auth + database)
- AI: OpenAI GPT-4 via API
- Voice Input: Web Speech API (Google Cloud later)
- Design: Natural-toned UI with parchment/leather aesthetic

---

## 🔐 Security Considerations
- Per-user data isolation via Supabase auth
- Voice input not stored unless opted in
- All external API keys securely managed

---

## 🚧 Development Milestones
- Day 1–2: Build Phase 1 (core functionality working end-to-end)
- Day 3–4: Prepare for Phase 2 integration
- Post-MVP: Expand, polish UI, add premium logic

---

## 🔮 Future Expansion
- Native mobile app
- Social discovery (friend libraries, shared lists)
- Reading streaks, badges, book club mode
