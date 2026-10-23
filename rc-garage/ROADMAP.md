# RC Garage roadmap

## Pull request 1 — Foundation and first playable prototype

- [x] Dedicated rc-garage project directory in BenchTools.
- [x] Responsive workshop interface and custom SVG short-course truck illustration.
- [x] Editable motor, ESC, battery, gearing, tire, and suspension catalog.
- [x] Component-driven estimates for the main setup metrics.
- [x] Canvas oval track, keyboard/touch controls, surface profiles, and basic vehicle dynamics.
- [x] Live instrumentation, simulated temperature estimates, lap timing, local configuration persistence, and JSON export.

## Pull request 2 — Saved build library and comparisons

- [x] Save named configurations locally in the browser.
- [x] Load and delete named setups.
- [x] Compare active and saved setup metrics side by side.
- [x] Import JSON setup files with catalog-ID and shell-color validation.
- [x] Keep JSON exports portable and document browser-local storage limitations.

## Later milestones

- Add structured test-run history with setup snapshots and lap-result summaries.
- Add repeatable acceleration and braking tests.
- Improve tire slip response and add more robust checkpoint timing.
- Add more layouts, surface-specific visuals, and setup presets.
- Improve detailed vehicle artwork and display additional installed-component changes.
- Add calculation and import/export tests.
- Keep the core app standalone and avoid runtime dependencies.
