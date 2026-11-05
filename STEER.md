URGENT bug from Paul: The Gemini API key never actually works. Fix that first.
Likely causes to check and fix:
1. Model id `gemini-2.5-flash` is retired for new users — switch default to a current free Gemini model (e.g. gemini-flash-latest or gemini-2.0-flash) that works with new keys, including keys that start with "AQ.".
2. Gemini streaming / SSE parsing may be wrong.
3. Empty/blocked replies from safety filters should fall through to the next provider instead of looking like a dead key.
4. Test button must clearly show why Gemini failed (HTTP status + short error), not a vague fail.
5. After fixing, keep other providers rotating as before.
