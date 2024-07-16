
# Updating the AI Art Gallery with Your Own Images

This guide provides step-by-step instructions to help you update the AI Art Gallery with your own images. Follow these steps to replace the existing images with your own creations.

## 1. Prepare Your Images
1. **Image Format**: Ensure your images are in a supported format (e.g., JPG, PNG).
2. **Thumbnail Size**: Create thumbnail versions of your images with a consistent size (e.g., 200x200 pixels).

## 2. Organize Your Images
1. **Directory Structure**: Place your images in the appropriate directories within the `images` folder. The directory structure should match the categories in the gallery.
    - `images/characters/`
    - `images/cityscapes/`
    - `images/indoors/`
    - `images/textures/`
    - `images/styles/`
2. **Naming Convention**: Name your images descriptively, following the pattern of existing files (e.g., `descriptive_name_tn.jpg`).

## 3. Update the HTML
1. **Open the HTML File**: Open the `index.html` file in a text editor or IDE.
2. **Locate the Image Sections**: Find the sections corresponding to each category:
    - Characters: `<section id="characters">`
    - Cityscapes: `<section id="cityscapes">`
    - Indoors: `<section id="indoors">`
    - Textures: `<section id="textures">`
    - Styles: `<section id="styles">`
3. **Replace Image Tags**: Update the `<img>` tags with the paths to your new images. For example:
    ```html
    <div><img src="images/characters/your_image_tn.jpg" alt="Description of your image" /></div>
    ```

## 4. Update the JavaScript (Optional)
If you have specific behaviors or interactions tied to the images, you may need to update the JavaScript file (`script.js`). Ensure the new images have the same class names or IDs used in the scripts.

## 5. Test Your Changes
1. **Open in Browser**: Open the `index.html` file in a web browser to preview your gallery.
2. **Check for Issues**: Verify that all images are displaying correctly and that the lightbox and navigation functions are working as expected.

## 6. Deploy Your Gallery
Once you are satisfied with the changes, deploy your updated gallery to your web server or hosting platform.

## Additional Tips
- **Image Optimization**: Optimize your images for the web to ensure fast loading times.
- **Accessibility**: Add descriptive `alt` text to your images for better accessibility.
- **Consistency**: Maintain a consistent style and size for all images to ensure a cohesive look.

By following these steps, you can easily update the AI Art Gallery with your own images and showcase your creative work.
