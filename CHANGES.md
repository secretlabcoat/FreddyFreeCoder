# Fixes (2026-11-05)

- Gemini default model changed from retired `gemini-2.5-flash` to `gemini-flash-latest`.
- Existing saved Gemini settings are migrated automatically to the new model.
- Gemini chat now merges back-to-back user/assistant messages (Gemini rejects same-role pairs, which made valid keys look broken).
- Clearer Gemini block/empty errors and longer Test button error text.
