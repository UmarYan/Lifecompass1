LifeCompass PWA v0.9

This update builds on v0.7 and consolidates the planned improvements into one package.
- Assessment ratings and reflections autosave locally; global and assessment save status indicators.
- Domain tabs show complete/partial state; assessment completion and answer counts remain visible.
- Dashboard includes overall scores, priorities, domain completion, and goal action progress summary.
- Goals retain start/target dates, status, milestones and actionable progress checkboxes.
- Upper-right menu icon groups navigation, install, backup/restore, CSV export, review snapshot, and report PDF actions.
- Existing assessment report, review comparison, history, PWA install support and local backup remain.

Deploy the extracted files to an HTTPS host (e.g. GitHub Pages). On Android Chrome, use Install App from the menu or browser menu > Add to Home screen.
Data is stored locally in this browser; export backups regularly.

Fix: Smart Priority Suggestions button and Add as 90-day priority actions now use robust delegated click handling; duplicate domain priorities are checked consistently (including legacy string domain values).


v0.9 button fix: individual Add as 90-day priority buttons now use direct click handlers. Suggest priorities adds the three lowest-scoring rated domains into the 90-day plan, skipping duplicates, and shows a confirmation. Apple/iOS-specific icons and metadata plus SVG icon are omitted; Android PNG icons remain.
