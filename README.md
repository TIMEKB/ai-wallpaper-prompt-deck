# AI Wallpaper Prompt Deck

This folder is designed to be published by GitHub Pages as static JSON.
The Android app default points to:

```text
https://timekb.github.io/ai-wallpaper-prompt-deck/manifest.json
```

## Publish

1. Edit `decks/prompt_deck_v1.json`.
2. Run:

```bash
python3 tools/validate_prompt_deck.py
```

3. Commit `.nojekyll`, `manifest.json`, `decks/prompt_deck_v1.json`, and this README to the GitHub Pages repository.
4. Enable GitHub Pages for the repository.

Generic App manifest URL format:

```text
https://<github_user>.github.io/ai-wallpaper-prompt-deck/manifest.json
```
