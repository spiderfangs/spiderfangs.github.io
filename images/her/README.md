# her world — images

Photos used by **princess mode** live here, kept separate from the dark-theme
images in `../` so you can change one world without touching the other.

By default princess mode just adds a soft pink tint to the existing photos.
To show *different* photos instead, drop your files here and turn the swap on:

1. Add the images below (any names work — just match the paths in the config).
2. In `index.html`, find the `HER_WORLD` config block and set
   `swapImages: true`, then point the paths at your files.

Expected files (defaults referenced by the config):

- `avatar.jpg`   — sidebar avatar
- `01.jpg` … `04.jpg` — gallery photos
- `bottom.jpg`   — the large bottom media

Missing files simply fall back to a `✦` placeholder, so nothing breaks if a
file isn't there yet.
