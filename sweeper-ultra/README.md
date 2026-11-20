# Sweeper Ultra: Google Play store listing

One folder per Play Console language (`play/<code>/`), all 41 languages of the game:
- `listing.json`: title, short description and full description
- `phone-01.jpg` … `phone-08.jpg` (1080 × 1920): phone screenshots with captions in that language and the game in that language
- `feature.jpg` (1024 × 500): the feature graphic

Made from the game's own Robolectric renders. The source text lives in the sweeperultra repo under `store/listing/`,
and the graphics are built by `tools/store/make_play_localized.py`.
