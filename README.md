# CTT Skilling LMS — Faculty Portal

A self-contained, single-file faculty portal for the L&T CTT Skilling LMS (UI prototype, sample data only).

- **Entry point:** `index.html` — no build step, no dependencies. Open it directly in a browser or deploy as a static site.
- **Stack:** vanilla HTML/CSS/JS single-page app.

## Deploy (Vercel)

```bash
npx vercel --prod
```

The repo is a plain static site, so Vercel serves `index.html` with no build.

## Features

Home dashboard, My Courses (course detail with Students / Course Content / Assessments tabs),
My Students, Assessments (MCQ test builder + course-wise results & scoring), Attendance,
Mentoring, Discussion Forum, Timetable, Events, and Raise a Case.
