# her world — audio

Music for **princess mode** lives here, kept separate from the original
tracks in `../`.

When you enter her world the player swaps to her playlist. Out of the box that
playlist reuses the existing songs in a softer order (so nothing extra is
required). To use her own songs instead:

1. Drop the `.mp3` files in this folder.
2. In `index.html`, find the `HER_WORLD` config block and update
   `music.tracks` to point at `audio/her/your_song.mp3`.

To keep the dark theme's music unchanged on toggle, set `swapMusic: false`
in the same config block.
