# IELTS VOCAB MEMORY

IELTS vocabulary flashcard app customized for memorization.

## Features

- Flashcards, quiz, searchable list, and custom words from the original app
- Memory hints with part of speech, word parts, core image, and related words
- Automatic migration from the old `ielts_v2` localStorage data when published on the same `cazy06.github.io` origin
- JSON export/import for moving learning progress between devices
- Google Sheets status CSV export
- Published vocabulary CSV at `data/ielts_vocab_words.csv`

## Data Migration

The original app stores progress in localStorage under `ielts_v2`.
This app stores its own data under `ielts_memory_v1`.

When opened on the same origin as the old app, this app automatically reads `ielts_v2` if `ielts_memory_v1` does not exist yet. The 管理 tab can also import old data manually.

If the app is published on another domain, use the 管理 tab to export/import JSON.
