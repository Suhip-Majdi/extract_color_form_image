🎨 Color Extraction from Images (extract_color_image)A lightweight, high-performance tool designed to isolate, extract, and analyze specific colors from input images. 
By leveraging computer vision and color segmentation algorithms, this project allows users to separate target color ranges from the background, mask out unwanted elements, and export the processed results or raw color data.

✨ Key FeaturesPrecise Masking: Extract colors using exact HSV (Hue, Saturation, Value) or RGB range configurations.
Dominant Color Identification: Analyze images to identify and rank the most frequently occurring color palettes.

Alpha Channel Support: Output extracted color layers with transparent backgrounds for graphic design workflows.
Batch Processing: Process large directories of images simultaneously via command-line arguments.
Format Versatility: 
Seamlessly handles common image formats including PNG, JPEG, WEBP, and BMP.


🚀 How It WorksColor Space Conversion: The script reads the target image and converts it into the HSV color space, which provides much more stable color segmentation than standard RGB.
Thresholding: A binary mask is created where pixels falling within the defined lower and upper color bounds are set to white, and all other pixels become black.Bitwise Extraction: 
The system applies the mask back onto the original image, filtering out the background and preserving only the selected color regions.

🛠️ Typical Use CasesComputer Vision Preprocessing: Isolating specific landmarks or objects (e.g., green screens, road lines, or medical markers) before feeding them into machine learning models.

Graphic & Web Design: Automatically generating color palettes or transparent asset elements directly from raw photography.E-commerce Automation:
Sorting and filtering product inventories based on primary item colors.
