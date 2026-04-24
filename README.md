# TruthGuard: Intelligent Fake News Detection Platform

TruthGuard is an AI-powered fake news detection platform that helps users check whether a news article is real, fake, or unclear. A user can paste a news article URL or text into the system, and TruthGuard analyzes the content, extracts the main claims, searches trusted sources on the web, compares the evidence, and returns a final verdict with a confidence score, summary, and supporting sources.

In addition to verification, the platform is designed to help users report suspicious or fake news so that others can refer to those reports in the future. This makes TruthGuard not only a detection tool, but also a growing awareness and reference platform.

## Project Members
1. Sayed Fatima Sultana Aslam [Team Leader]
2. Ansari Jafeera Jamil Ahmed
3. Raza Tahiya Ishaque

## Project Guide
1. Prof. Mansi Trivedi [Primary Guide]

## Subject Details
- Class: TE (AI&DS) Div A - 2025-2026
- Subject: Mini Project Lab: 2B (AI&DS) (MP 2B (A)(R19))
- Project Type: Mini Project

## Problem Statement
Fake news spreads very quickly across digital platforms and often reaches people before the truth does. Many users find it difficult to manually verify whether a news article is trustworthy, especially when multiple websites repeat the same claim. TruthGuard aims to solve this problem by combining AI-based content analysis with multi-source verification and explainable results.

## Objectives
- Detect whether a news article is real, fake, or unclear
- Extract important claims from article content
- Cross-check article claims using multiple web sources
- Generate a clear verdict with confidence score
- Provide a short summary and supporting evidence to the user
- Allow suspicious or fake news to be reported for future reference

## Key Features
- URL-based and text-based news checking
- AI-powered article understanding
- Claim extraction and comparison
- Multi-source web verification
- Verdict generation: Real / Fake / Unclear
- Confidence score for evidence strength
- Article summary generation
- Source-backed explainable results
- Fake news reporting for community reference

## How It Works
1. The user enters a news article URL or pastes article text.
2. The system extracts the article content and metadata.
3. AI analyzes the text and identifies the main claims.
4. Trusted web sources are searched for related information.
5. The system compares the article’s claims with external sources.
6. A final verdict, confidence score, summary, and supporting sources are shown to the user.

## Technology Stack

### Frontend
- TanStack Start
- React
- TypeScript
- Tailwind CSS

### Backend
- Node.js
- REST APIs / Server-side routes

### AI and Analysis
- Anthropic Claude SDK
- Natural Language Processing (NLP)
- Claim extraction and semantic analysis

### Verification and Search
- Web Search APIs
- Content extraction and scraping pipeline
- Cross-source verification engine

### Deployment
- Vercel / Cloud deployment
- Modern browser-based interface

## Platform, Libraries, and Frameworks Used
1. [Node.js](https://nodejs.org/)
2. [TanStack Start](https://tanstack.com/start)
3. [React](https://react.dev/)
4. [TypeScript](https://www.typescriptlang.org/)
5. [Tailwind CSS](https://tailwindcss.com/)
6. [Anthropic Claude SDK](https://www.anthropic.com/)
7. Web Search APIs

## System Modules
- User Input Module
- Article Extraction Module
- AI Analysis Module
- Claim Detection Module
- Web Search Module
- Cross Verification Module
- Verdict and Confidence Module
- Fake News Reporting Module

## Deployment Steps

### Prerequisites
- Node.js installed
- npm or bun installed
- Internet connection
- API keys for AI model and web search service

### Steps
1. Clone the repository
```bash
git clone <your-repository-link>
cd truthguard
