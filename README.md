# Infosys Career Cracker

A personal placement-prep coach for BCA students aiming for software roles, including Infosys. It tracks your real progress, plans each day around your weakest areas, and gives you an honest readiness score.

🔗 **Live demo:** https://smiling-coder.github.io/infosys-career-cracker/

![Dashboard screenshot](screenshots/dashboard.png)

## Features

- **Personal profile:** semester, skills, study hours and target role shape your plan.
- **Dashboard:** readiness ring, skill radar, streak, next best action and weekly activity. Cards can be dragged to rearrange, and the layout is saved.
- **Daily mission:** coding, aptitude, technical, project, GitHub, communication and revision tasks.
- **Adaptive plan:** weaker skills get focus tasks, so every student's roadmap differs.
- **Problem solving:** 15 coding problems with test cases, hints on request and complexity analysis.
- **Aptitude lab:** timed quantitative, logical and verbal tests with explanations.
- **Project builder:** 9 projects across three levels, unlocked milestone by milestone, with a quality checker scored out of 100.
- **GitHub trainer:** Git lessons, weekly assignments and a readiness score.
- **Resume builder and reviewer:** ATS score and four resume versions.
- **Interview room:** technical and HR simulators, project defense mode and an English speaking trainer.
- **Career mentor:** answers from your own progress data.
- **Light and dark mode**, mobile-first layout.

## Honest by design

- The readiness score comes only from work you complete.
- The app does not promise a job, a salary or selection.
- All questions are practice material, not real company papers.
- Check the official Infosys careers site for current recruitment details.

## Tech stack

- HTML, CSS and vanilla JavaScript
- No backend and no build step
- Progress is saved in the browser's `localStorage`

## Project structure

```
infosys-career-cracker/
├── index.html
├── style.css
├── script.js
├── screenshots/
│   └── dashboard.png
└── README.md
```

## Run locally

```
git clone https://github.com/smiling-coder/infosys-career-cracker.git
cd infosys-career-cracker
```

Then open `index.html` in your browser.

## Known limitations

- Coding problems use JavaScript so they can run in the browser.
- Data stays on one device and browser. There is no login or sync yet.
- Mentor and interview feedback are rule-based, not a live AI model.

## Future plans

- Python and C# problem runner
- More problems and aptitude questions
- Login and cloud sync
- Live AI mentor

## Author

Built by [smiling-coder](https://github.com/smiling-coder) as a placement-preparation project.
