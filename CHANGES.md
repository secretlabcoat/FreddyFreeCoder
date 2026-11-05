# Fixes (2026-11-05)

- Gemini: retired `gemini-2.5-flash` → `gemini-flash-lite-latest` (verified).
- Groq: retired `llama-3.3-70b-versatile` → `openai/gpt-oss-20b` (verified).
- OpenRouter: unavailable free Llama slug → `openrouter/free` (verified), plus Referer/Title headers.
- Saved provider settings are migrated off the old model ids automatically.
- Gemini same-role message merge; clearer API error text on Test / chat failures.
