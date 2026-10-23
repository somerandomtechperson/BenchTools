# RC Garage

**Build. Tune. Test.** A standalone RC short-course truck configurator and physics-informed driving simulation.

RC Garage is part of the BenchTools collection. It runs from one HTML file with inline CSS and JavaScript. There is no framework, build step, backend, external asset, or network dependency.

## Open it

- **GitHub Pages:** after the repository's Pages site is enabled, open the RC Garage path in the published site.
- **Local:** download the index.html file and open it in a modern browser.
- **Controls:** use W/A/S/D or the arrow keys to drive, R to reset, C to switch camera mode, and Space to pause or resume while on the track. Touch controls are available in the app.

## Current prototype

- A configurable 1/10-scale-style 4WD electric short-course truck.
- Brushless motor, ESC, LiPo battery, gearing, tire, and suspension options.
- Calculated top-speed, gear-ratio, mass, power, cost, and runtime estimates.
- Canvas-based oval test track with packed dirt, loose dirt, clay, asphalt, and grass profiles.
- Keyboard and touch controls, acceleration, braking/reverse, steering, boundary contact, lap timing, and chase/trackside camera modes.
- Live speed, battery voltage sag estimate, current estimate, and motor/ESC temperature models.
- Recent telemetry chart, browser-local configuration persistence, and JSON build export.
- Five body finishes and a responsive workshop interface.

## Engineering notes

This is an interactive prototype, not a validated digital twin or professional RC setup tool. Component names and specifications are illustrative unless explicitly verified. Speed, current, voltage sag, temperature, runtime, grip, and handling are modeled estimates. Real results depend on motor curves, battery condition, ESC programming, tire compounds, suspension geometry, terrain, and other factors.

The driving model uses simplified vehicle dynamics and a fixed physics timestep. The garage uses scalable SVG artwork; the driving view is rendered locally on Canvas. The project intentionally avoids external libraries and assets to keep direct-file use reliable.

## Roadmap

1. Foundation: garage, editable parts catalog, connected performance estimates, and first playable track prototype.
2. Engineering workflow: named configurations, import/export validation, setup comparisons, repeatable test summaries, and stronger telemetry.
3. Simulation refinement: improve grip and slip behavior, checkpoint timing, suspension response, and repeatable acceleration/braking tests.
4. Polish: more track layouts, better component details, more setup metadata, accessibility checks, and performance tuning.

## Privacy and storage

Automatic build persistence uses this browser's localStorage. Data is local to the browser and does not synchronize across devices. JSON export provides a portable copy. If local storage is blocked, component editing and simulation still work during the current session.

## License

See the repository's top-level LICENSE.
