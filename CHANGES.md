# Fixes (2026-11-05)

- Gemini was calling retired `gemini-2.5-flash` (HTTP 404 for new keys). Default is now `gemini-flash-lite-latest`, which replies successfully.
- Saved Gemini settings are migrated off the retired model automatically.
- Gemini chat merges back-to-back same-role messages (Gemini rejects those, which also made valid keys look broken).
- Clearer Gemini block/empty errors and longer Test button error text.
