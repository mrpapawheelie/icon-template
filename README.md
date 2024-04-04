# Icon Template Guides

This guide outlines how to properly design logos or icons in various shapes. It includes one vector ai file with the guides, and multiple Display P3 color profile templates as psd's. Follow this guide will ensure your logo or icon is properly sized and contains the crrect color profile for high res icons required by Apple.

## Exporting SVG from Adobe Illustrator

1. Open the `.ai` icon template in Adobe Illustrator.
2. Once you've customized your icon within the template's guides, go to `File` > `Save a Copy...`.
3. In the dialog, select `SVG (*.SVG)` as the format and click `Save`.
4. In the SVG options, leave the settings at their default values and click `OK`.

## Creating PNG Versions

To create PNG versions of your icon in the necessary sizes (32px, 64px, 128px, 256px, etc.), follow these steps:

### Step 1: Exporting from Adobe Illustrator

1. Ensure each version of your icon is aligned within the square, circle, tall rectangle, wide rectangle, and square guides provided in the template. Use the locked layer for guides.
1. To hide any unused shapes, unlock the guide layer, and click the eye icon next to the shapes you do not need. **Remember to hide the entire layer before saving.**

### Step 2: Adjusting Color Profile in Adobe Photoshop

1. Create a new file for each size ensure you choose Display P3 color profile.
2. Drag your svg icon into a psd, this will ensure it's perfectly sized.
3. Click the checkbox to confirm, then go to `Edit` > `Convert to Profile` and choose `Display P3`
4. Go to `File` > `Save a Copy...` (You must choose save a copy option and no other exporting option in order to see Display P3).
5. Choose `PNG (*.PNG)` as the format.
6. Before saving, make sure to check the option `Use the Display P3 color profile` to ensure color accuracy across devices.

## Additional Notes

- The template includes a main square container with accurately portioned guides for a circle, tall rectangle, wide rectangle, and a square. Your shapes should fit within these guides without alteration.
- The guides are on one locked layer for your convenience. You can unlock this layer if necessary, but remember to hide it completely before exporting your final icon versions.

By following these steps, you will ensure your icons are exported with the highest fidelity and color accuracy, ready for use in your applications or websites.
