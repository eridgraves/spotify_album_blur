# Recreating Spotify's Album Art Blur

- Spotify's iOS app automatically generates a background glow around the album art of the currently playing song.
- This is somehow related to the colors present in the artwork, but not necessarily an exact replication of the art (like android's scale and blurred art when playing)
- Sometimes it seems like its able to catch highlight/accent colors, other times, it is just the most prevalent color.
- This project is my attempt to write code that generates a glow color from colors in an album cover.


## Contents:
- Images: 
    - 9 Screenshots of random album art from my phone, including 2 songs on the same album, which share the same art, but have different glow colors.
    - 8 Images of album art from the screenshots.
- Code: 
    - **spotify_album_blur.md** the README file for this project.
    - **requirements.txt** environment packages used in development.
    - **album_blur.ipynb** jupyter notebook with the actual code.
