# Super Cyphs 64 - Cole Build Notes

This is a source-only edit of the uploaded SM64 Toolgun decomp project. It does not include a ROM or baserom.

## Added branding

- Press-start screen overlay now says `SUPER CYPHS 64`.
- Toolgun pause menu credit now says `Super Cyphs 64 Toolgun - Cole Build`.

## Added toolgun menu items

Use the Tool Gun pause-page, then D-Pad Left/Right to select items and press L in-game to place.

New items added after the original 20:

21. Anthony
22. Cole
23. Alec
24. Nain
25. Caine
26. Geek Bar
27. Lucky 7 Smoke Shop
28. Cart
29. Guns
30. Yoyo Chicken Store
31. Evil Foe-id
32. Foe-id Bob-Omb
33. Foe-id Fly Guy

## Placeholder asset note

No new 3D models/textures were supplied, so these are wired to existing global or already-used SM64 Toolgun models as placeholders. The names show up in the Toolgun menu and the source is set up so the placeholder model IDs can be replaced later with real imported Fast64/Blender actors.

## Enemy replacement

Common enemy behaviors are visually remapped to the neutral `Foe-id` placeholder model. Their original behavior/hitboxes remain intact so levels should keep functioning. Special boss logic is mostly left alone to reduce softlock/crash risk.

I used `Foe-id` rather than a gender-targeted/dehumanizing term, so the mod can stay as a general enemy reskin.
