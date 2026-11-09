# Changelog

## v1.2 – 2026-11-09

- **PlayStation**: Start and Select now look like the real DualSense keys: a tall pill with the three printed lines above it (Options) or the three printed rays above it (Create), with no round badge. On the "Basic Controls" screen the face-button diamond is bigger and fully encloses ○ ✕ △ □, and the guide lines now touch the diamonds.
- **Xbox**: Start and Select now look like the real keys: a round key with a light Menu or View icon, its dark face left transparent.
- **Steam Deck**: on the "Basic Controls" screen, the Pro Controller shadow behind the picture is gone, and the picture, its diamonds and its guide lines are about 20% larger.
- Files changed: PlayStation font and `Common.Product.100.*.bntx.zs`, Xbox font, Steam Deck `Common.Product.100.*.bntx.zs`. The icons of the other buttons and the ocarina song sheets are unchanged.

## v1.1 – 2026-11-08

- **Ocarina song sheets**: the notes on the play screen (staff notation) still showed the Switch buttons, because they come from their own textures (`OcarinaButton{A,B,X,Y,L,R}_00`) rather than the glyph font. They now follow each mod's mapping: PlayStation ○ ✕ △ □ + L1/R1, Xbox B/A/Y/X + LB/RB, Steam Deck B/A/Y/X + L1/R1. The melody symbols (Triforce, Epona, etc.) are unchanged. Preview: `previews/preview-ocarina.png`.
- Only the `Common.Product.100.*.bntx.zs` in each folder changed; the font is the same as in v1.0.

## v1.0 – 2026-11-07

- First release: in-game button icons (glyph font + HUD textures) and the controller drawing on the "Basic Controls" screen for PlayStation (DualSense), Xbox and Steam Deck.
