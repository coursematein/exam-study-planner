# Exam Study Planner

A lightweight, mobile-friendly study planner for competitive-exam preparation.

The project runs entirely in the browser and stores study data locally. No account, backend, or server database is required.

## Version 2.8

### Advanced Dashboard
- Exam target countdown with days remaining / target-date status
- Today's planned study hours and task completion
- Overall study-task completion percentage
- Next-action guidance based on current preparation status
- Recent mock-test summary on the dashboard
- Existing weak-topic tracking retained
- Existing v2.7 mock-test validation, negative marking, accuracy and score calculations retained
- Existing revision tracker and local browser data retained

## Data and compatibility

Study data is stored in browser Local Storage under the same `examStudyPlanner.v2` key used by v2.7. Updating the application does not intentionally clear existing v2.7 data on the same browser/device.

If the app is opened on a different browser/device, local study data will not automatically appear because it is browser-local.

## Running locally

Open `index.html` in a modern browser. No installation or build process is required.

## GitHub Pages

Upload `index.html`, `README.md`, and `CHANGELOG.md` to the repository root. GitHub Pages can serve `index.html` directly.

## Privacy

Study data remains in the browser. The application does not require an account or send study records to a server.

## Technology

- HTML
- CSS
- JavaScript
- Browser Local Storage
- GitHub Pages

## License

MIT License.
