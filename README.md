# اختبار أخلاقيات المعلومات

Interactive Arabic RTL quiz on **Information Ethics** (أخلاقيات المعلومات).

## Live Demo

Enable GitHub Pages once: **Settings → Pages → Source: Deploy from a branch → `main` / root → Save**

Then open:

**https://osama-bakri.github.io/information-ethics-quiz/**

## Features

- Three progressive exams (short answers, True/False, matching, MCQ)
- **Instant auto-scoring** for objective questions with green/red feedback
- Short-answer questions collected for teacher review (model answers shown)
- Student name gate + live progress bar + final badge
- Results saved to **localStorage** (works offline and online)
- Teacher dashboard (type `teacher` or `مدرس` anywhere, password: `teacher2026`)
- Fully self-contained single HTML file — no server needed

## How students use it

1. Open the page and enter their full name
2. Answer the questions (objective ones score instantly)
3. Click **إرسال نتيجتي للمدرّس** to save the result

## How teachers use it

1. Open the same page in the browser
2. Type the word **teacher** (or Arabic **مدرس**) anywhere on the page
3. Enter password: `teacher2026`
4. View all submissions stored in that browser, expand answers, or clear data

> Results are stored per-browser via localStorage. For a real multi-device classroom, either collect screenshots or host a version with a shared backend (Firebase, Supabase, etc.).
