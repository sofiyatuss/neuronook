# NeuroNook V2 — Pixel Clinic

Open NeuroNook_V2.html in a modern browser. No server, Python installation, account, or paid API is required.

Features: 52 fictional clinical cases, five progressive levels, searchable learning guide, patient interview, focused exam, two authored investigations per case, synthetic educational illustrations, interpretation exercises, differential tracking, free-text and multiple-choice diagnosis, scoring, and browser-local saved progress.

Important: This is an educational simulation, not a diagnostic medical tool. Visual test schematics are decorative, not real clinical images. The authored test descriptions provide the clinically meaningful results. Case accuracy has not undergone expert clinical validation.

Progress is saved in localStorage; use the export/import controls to back it up. V2 reuses the V1 progress key to preserve your progress in the same browser origin. Local file origins and iPad browser storage can behave differently.

Source links are included in sources.json. Cases are fictional composites and are not individual published patient records.

For editing: template_v2.html contains __CASES__ and __SOURCES__ placeholders. The playable HTML embeds the full data. v2_logic.js contains the updated clinical game engine.
