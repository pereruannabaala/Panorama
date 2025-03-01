# Image Stitching with OpenCV

## Overview
This project demonstrates how to download image assets, load them using OpenCV, and stitch them together to create a panorama using OpenCV's Stitcher module. The images are extracted from a ZIP file, processed, and then displayed using Matplotlib.

## Requirements
Ensure you have the following libraries installed before running the script:
- OpenCV (cv2)
- NumPy (numpy)
- Matplotlib (matplotlib)

## How It Works
1. Download and Extract Assets
- The script downloads a ZIP file containing image assets from Dropbox.
- The contents are extracted to the current working directory.
2. Load Images
- The images are read from the boat directory using OpenCV.
- They are converted from BGR to RGB for correct visualization.
3. Display Images
- The individual images are displayed using Matplotlib.
4. Image Stitching
- OpenCV's Stitcher module is used to combine multiple images into a panorama.
- If successful, the stitched image is displayed.
## Expected Output
- The script will first display the individual images.
- If stitching is successful, the final panorama image will be shown.
## Troubleshooting
- Ensure all images are in the correct directory (boat/).
- If stitching fails, check that the images overlap sufficiently.
- Ensure OpenCV is correctly installed and supports Stitcher_create().
## License
- This project is open-source and available for personal and educational use.
## Author
- Pereruan Nabaala
- pereruannabaala@gmail.com
: smile