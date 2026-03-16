<div align="center">

<img src="https://img.shields.io/badge/-Next.js_16-000000?style=for-the-badge&logo=next.js&logoColor=white" />
<img src="https://img.shields.io/badge/-ElevenLabs-FFFFFF?style=for-the-badge&logo=elevenlabs&logoColor=black" />
<img src="https://img.shields.io/badge/-Vapi-62F6B5?style=for-the-badge&logo=vapi&logoColor=black" />
<img src="https://img.shields.io/badge/-Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white" />

<br/>

<img src="https://img.shields.io/badge/-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/-Typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/-Tailwind-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white" />
<img src="https://img.shields.io/badge/-Shadcn/UI-000000?style=for-the-badge&logo=shadcnui&logoColor=white" />

</div>

<h1 align="center">📚 AI Book Companion</h1>

<h3 align="center">Vapi • ElevenLabs • Next.js</h3>



---

## 📋 Table of Contents

1. ✨ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)

---

# ✨ Introduction

**Bookified** is an AI-powered platform that lets you have real-time voice conversations with your books.

Built with **Next.js 16, Vapi, ElevenLabs, and MongoDB**, it transforms PDFs into interactive AI-powered entities using natural voice synthesis.

Users can:

- Upload books
- Ask questions using voice
- Generate summaries
- View conversation transcripts
- Interact with different AI voice personas

All wrapped in a sleek UI built with **Shadcn and Tailwind CSS**, secured with **Clerk authentication**.

---

# ⚙️ Tech Stack

### Clerk
[Clerk](https://clerk.com)

A complete authentication and user management platform providing:

- Email login
- Social authentication
- Session management
- Secure protected routes

---

### CodeRabbit
[CodeRabbit](https://jsm.dev/books-coderabbit)

An AI-powered code review platform that:

- Provides automated pull request reviews
- Suggests optimizations
- Detects bugs
- Improves code quality

---

### ElevenLabs
[ElevenLabs](https://elevenlabs.io/docs)

A powerful **AI voice generation platform** used for:

- Realistic voice synthesis
- Voice previews
- AI voice personalities

---

### MongoDB
[MongoDB](https://www.mongodb.com/docs)

A scalable NoSQL database used to store:

- User libraries
- Book metadata
- Conversation transcripts
- AI embeddings

---

### Next.js
[Next.js](https://nextjs.org/docs)

A React-based full-stack framework providing:

- Server-side rendering
- API routes
- High performance
- Modern web architecture

---

### Shadcn UI
[Shadcn UI](https://ui.shadcn.com)

A modern component library built on:

- Tailwind CSS
- Radix UI

Used to create a **clean and professional interface**.

---

### TypeScript
[TypeScript](https://www.typescriptlang.org)

A strongly typed JavaScript superset providing:

- Static typing
- Better developer experience
- Improved maintainability

---

### Vapi
[Vapi](https://vapi.ai)

A **Voice AI platform** enabling:

- Real-time voice conversations
- Low-latency audio streaming
- AI-powered dialogue systems

---

# 🔋 Features

### 📄 PDF Upload & Ingestion
Upload books with automated:

- text extraction
- chunking
- embeddings generation

---

### 🎙 Voice Conversations
Talk with your books using **natural real-time voice conversations** powered by Vapi.

---

### 🧠 AI Voice Personas
Choose from multiple **AI personalities** powered by ElevenLabs.

---

### 📑 Smart Summaries
Generate:

- chapter summaries
- concept explanations
- key insights

---

### 📝 Session Transcripts
Every conversation is automatically converted into **text transcripts**.

---

### 📚 Library Management
Manage your uploaded books with an **organized searchable library**.

---

### 🔐 Authentication
Secure login using:

- Email
- Social providers

Powered by **Clerk**.

---

# 🤸 Quick Start

Follow these steps to run the project locally.

---

## Prerequisites

Install the following:

- Git
- Node.js
- npm

---

## Clone the Repository

```bash
git clone https://github.com/gauravsinghcodes/bookified.git
cd bookified
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
NODE_ENV='development'
NEXT_PUBLIC_BASE_URL=

# CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# VERCEL BLOB
BLOB_READ_WRITE_TOKEN=

# MONGODB
MONGODB_URI=

# VAPI
NEXT_PUBLIC_VAPI_API_KEY=
NEXT_PUBLIC_ASSISTANT_ID=


```

Replace the placeholder values with your real credentials. You can get these by signing up at: [**Clerk**](https://clerk.com), [**Vercel**](https://vercel.com), [**MongoDB**](https://www.mongodb.com), [**Vapi**](https://vapi.ai), [**Google AI Studio**](https://aistudio.google.com), [**ElevenLabs**](https://elevenlabs.io).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
