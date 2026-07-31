# Text Study — Paste & Learn

A single-page study tool. Paste any English text, then tap a word or sentence to
look it up, translate it, or ask Claude to explain it in context.

**Live:** https://shiryu2005111-cmd.github.io/text-study/

## Notes

- Everything runs in your browser. Nothing is uploaded to this site.
- Your pasted text and saved answers are stored in your own browser
  (`localStorage`) and never leave your device except for the lookups below.
- The AI explanation feature calls the Anthropic API **directly from your
  browser** using an API key you supply yourself. The key is stored in your
  browser's `localStorage` only — it is not part of this repository and is never
  sent anywhere except to Anthropic. Get one at console.anthropic.com → API keys.
  Usage is billed to your own account.
- Dictionary lookups use dictionaryapi.dev; translation uses Google Translate.

## Licence

Personal project. Use at your own risk.
