# Changelog

## v1.1 – 2026-11-08

- **Ocarina song sheets**: the notes on the play screen (staff notation) still showed the Switch buttons, because they come from their own textures (`OcarinaButton{A,B,X,Y,L,R}_00`) rather than the glyph font. They now follow each mod's mapping: PlayStation ○ ✕ △ □ + L1/R1, Xbox B/A/Y/X + LB/RB, Steam Deck B/A/Y/X + L1/R1. The melody symbols (Triforce, Epona, etc.) are unchanged. Preview: `previews/preview-ocarina.png`.
- Only the `Common.Product.100.*.bntx.zs` in each folder changed; the font is the same as in v1.0.

## v1.0 – 2026-11-07

- First release: in-game button icons (glyph font + HUD textures) and the controller drawing on the "Basic Controls" screen for PlayStation (DualSense), Xbox and Steam Deck.
