# Exam Study Planner

A lightweight, mobile-friendly study planner for competitive-exam preparation.

The project runs entirely in the browser and stores study data locally. No account, backend, or server database is required.

## Features

- Create and manage exams with target dates and daily study hours
- Organize preparation into subjects and topics
- Mark topics as completed
- Identify and track weak topics
- Create daily study tasks
- Track three-stage revision cycles
- Record mock-test performance
- Validate mock-test question counts
- Calculate attempted and unattempted questions
- Calculate accuracy
- Support configurable negative marking
- Track mock-test history and performance
- View overall preparation progress from the dashboard
- Responsive mobile-first interface
- Local browser storage for personal data

## Mock-test calculations

The planner distinguishes between:

- **Correct** — questions answered correctly
- **Wrong** — questions answered incorrectly
- **Unattempted** — total questions minus correct and wrong
- **Accuracy** — correct ÷ attempted × 100
- **Score** — calculated using the selected negative-marking rule

The application prevents invalid entries when the number of attempted questions exceeds the total number of questions.

## Privacy

Study data is stored locally in the browser. The application does not require an account or send study records to a server.

## Technology

- HTML
- CSS
- JavaScript
- Browser Local Storage
- GitHub Pages for static hosting

## Running locally

Download `exam-study-planner-v2-7.html` and open it in a modern browser.

No installation or build process is required.

## GitHub Pages

The project can be published as a static GitHub Pages site directly from the repository.

## Project status

This is an actively developed personal/open-source study-planning project. Future improvements may include data export/import, richer analytics, reminders, accessibility improvements, and additional exam-specific configuration.

## Contributing

Suggestions, bug reports, and improvements are welcome. Please open an issue or pull request with a clear description of the proposed change.

## License

MIT License.
