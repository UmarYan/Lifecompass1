LifeCompass PWA v0.12 — Debug Mode

Built from the v0.11 base. Adds a phone-accessible Debug Mode to help investigate Smart Priority button failures.

Debug Mode (upper-right menu > Debug Mode / Error Log):
- Captures technical click/action trace for Add as 90-day priority and Suggest priorities.
- Captures JavaScript window errors and unhandled promise rejections.
- Includes save/render failures and stack traces when available.
- Copy Error Log copies the trace; Clear Log clears it; Close hides the panel.
- Logs are kept in memory for this page session and do not include Assessment ratings or reflection text.

How to reproduce and share the issue:
1. Deploy all files to HTTPS GitHub Pages.
2. Open LifeCompass and navigate to Smart Priority Suggestions.
3. Open upper-right menu > Debug Mode / Error Log.
4. Tap Add as 90-day priority or Suggest priorities.
5. Reopen Debug Mode, tap Copy Error Log, and paste the copied log into ChatGPT.

Existing data, assessment, goals, review history, reports, backup/restore, menu, and Android PWA install support are retained. Android PNG icons only; Apple-specific icon and SVG assets are omitted.

Validation: JS syntax, Service Worker syntax, Manifest JSON, and ZIP integrity checked. Browser/device testing not performed.
