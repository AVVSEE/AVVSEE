How to Use:

Upload Image & View Results:

1.   Locate the cell with the description "Upload Image"

2.   Choose your desired image from your computer.


Once the image is uploaded, the notebook will automatically process it. The uploaded image will be displayed, followed by its dominant colors and complementary colors. The colors are presented as rectangular blocks with labels indicating whether they're dominant or complementary.

To analyze a different image, simply use the "Upload" button again to select a new image. The results will update automatically. Technical Details:

Dominant Colors: These are extracted using the K-means clustering algorithm, which groups pixels in the image based on color. The center of each cluster represents a dominant color. Complementary Colors: For each dominant color, the complementary color is calculated by taking the inverse in the RGB color space.

Notes: The tool currently extracts three dominant colors from each image. This number can be adjusted in the code if needed.

The quality and accuracy of the results may vary depending on the image. For best results, use clear images with distinguishable colors
