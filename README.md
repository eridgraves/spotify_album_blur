# Recreating Spotify's Album Art Blur

- Spotify's iOS app automatically generates a background glow around the album art of the currently playing song. I first became interested in Spotify's implementation of this feature when I noticed that the glow color of Brockhampton's "Saturation III" was different for different songs. (as of 09/07/2019 Spotify has since fixed this bug)
- This is somehow related to the colors present in the artwork, but not necessarily an exact replication of the art (like android's scale and blurred art when playing)
- Sometimes it seems like its able to catch highlight/accent colors, other times, it is just the most prevalent color.
- This project is my attempt to write code that generates a glow color value from colors in an album cover.


## Contents:
- Images:
    - 9 Screenshots of random album art from my phone, including 2 songs on the same album, which share the same art, but have different glow colors.
    - 8 Images of album art from the screenshots.
- Code:
    - **spotify_album_blur.md** the README file for this project.
    - **requirements.txt** environment packages used in development.
    - **album_blur.ipynb** jupyter notebook with the actual code.
    

## Project Status/Notes:

Last update: September 9, 2019
- I am happy with the functionality of the code as it stands here. It was a good hand-on example of image-processing techniques and thinking of how a large company would implement such an easy to overlook feature. 


## Future Improvements:
- Create mock-up UI from the extracted highlight colors. (Seems relatively straightforward and not really in my area of interest)
- Fine-tune image scaling and k-means clusters parameters.
    - These have a large impact on which colors are produced. I noticed while testing that colors would be removed during scaling and clusters would move to non-existent colors while calculating means. 
- Look into other ways of determining the most prominent color.
