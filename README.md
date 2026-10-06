# AI Student Practical Suite

A single-page web application that combines 10 practical AI-style student tools into one interface. It is designed as a lightweight academic utility dashboard for generating resumes, notes, presentations, quiz questions, flashcards, study plans, and more.

## Features

1. Resume Builder
   - Create a student or professional resume from basic details
   - Supports education, skills, experience, projects, and objective

2. Notes Generator
   - Converts pasted text into concise study notes
   - Highlights key points and revision summary

3. Presentation Generator
   - Builds a simple six-slide deck for any topic
   - Includes introduction, concepts, applications, challenges, and conclusion

4. Mind Map Generator
   - Organizes syllabus or concept lists into a visual topic tree

5. Google Sheets Data Demo
   - Adds student marks to a local in-browser data table
   - Provides a simple average/highest-score insight summary

6. Quiz / MCQ Generator
   - Generates a basic multiple-choice quiz for a topic
   - Tracks score after user answers

7. AI Chatbot
   - Responds with demo educational answers for common subjects
   - Useful for quick concept explanations and revision

8. Flashcard Generator
   - Creates topic-based flashcards for revision practice
   - Includes flip, previous, next, and shuffle controls

9. Study Planner
   - Generates a weekly timetable based on subjects and daily hours

10. OCR Notes Summarizer
   - Accepts uploaded notes images and/or pasted OCR text
   - Produces a condensed summary of key takeaways

## Tech Stack

- HTML
- CSS
- JavaScript
- Python HTTP server for local running

## Project Structure

- `main.html` — complete app interface and JavaScript logic
- `README.md` — project overview and usage instructions

## How to Run

From the project folder:

```bash
cd /workspaces/ai-tool
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Notes

This project is a frontend demo and does not require a backend or database setup. It runs entirely in the browser and stores data in JavaScript memory while the page is open.

## Use Case

This app is useful for:

- student practical assignments
- academic revision tools
- quick AI-inspired productivity demos
- classroom presentation and study support

## License

This project is provided as a learning/demo project for educational purposes.
