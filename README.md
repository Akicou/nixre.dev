# nixre.dev

Static landing page for [Nixre](https://github.com/Akicou/Nixre), a self-hosted Git forge. Live at https://nixre.dev.

- `index.html`: the page, no build step
- `llms.txt`: install guide for agents, synced from the main repo
- `img/`, `media/`: screenshots (sample data) and the promo video

Any static host works.

## Promo video

`media/nixre-promo.mp4` is generated, not edited by hand. To rebuild it after a big UI change, use the skill [Lyan/motion-promo-video](https://git.nixre.dev/Lyan/motion-promo-video) (start with its `references/nixre-video.md`). Screenshots in `img/` come from the same skill. The video's music is third-party; keep the credit in `media/CREDITS.md`.

## License

MIT © 2026 Nixre Contributors, except the music in `media/nixre-promo.mp4` ("Double Rum Cola" by FATA BOOM), which is third-party. See [media/CREDITS.md](media/CREDITS.md).
