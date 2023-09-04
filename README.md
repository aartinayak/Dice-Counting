# Dice-Counting

## Description

This MATLAB script is designed to count the number of dice in a given image, report the number of each type of die (1-6), and calculate the total number of dots on all the dice in the image. The script uses image processing techniques to detect and analyze dice patterns.

## Prerequisites

Before using the script, ensure you have the following prerequisites:

* MATLAB: You need MATLAB installed on your computer to run this script.
  * If you do not have MATLAB installed on your system, you can check out the steps <a href="https://www.mathworks.com/products/matlab.html?s_tid=hp_products_matlab">here</a>.

* Input Images: Prepare the input images that contain the dice you want to analyze. Supported image formats include JPEG, PNG, and others.
  * The darker your background is in comparison to your dice, the better segmentation this particular script can achieve for you.
  * For example: The images I was working with images that looked something like this:

    
<img src="https://github.com/aartinayak/Dice-Counting/blob/main/images/SampleImage.png" width = 50% height = 50%>

## Usage

1. Clone or Download the Repository: Clone the repository containing the MATLAB script to your local machine or download it as a ZIP file and extract its contents.

```bash
git clone https://github.com/aartinayak/Dice-Counting.git
```

2. Prepare Input Images: Place your input image files in the same directory as the script. Alternatively, you can specify the file paths within the script.

3. Run the Script: Open MATLAB and navigate to the directory containing the script. Run the script by typing the following command in the MATLAB command window, replacing 'your_image.jpg' with the path to your input image file:

```matlab
count_dice('your_image.jpg');
```

4. Review the Results: The script will process the input image and provide the following information:

    * Total number of dice detected in the image.
    * Number of dice for each type (1-6) detected in the image.
    * Total number of dots counted on all the dice in the image.

5. Customize Parameters (Optional): You can customize the script by adjusting image processing parameters to optimize dice detection for specific image conditions, resolutions, or backgrounds.

6. Evaluate the Output: Review the output generated by the script to gain insights into the number and distribution of dice in the provided image and see if you need to tweak the parameters a bit.

## Examples

Here is an example image and its expected output:

<img src="https://github.com/aartinayak/Dice-Counting/blob/main/images/OutputImage.png" width=50% height=50%>
<img src="https://github.com/aartinayak/Dice-Counting/blob/main/images/OutputCount.png" width=50% height=50%>

## Customization

You can tailor the script to suit your specific requirements by:
 * Adjusting image processing parameters to optimize dice detection.
 * Modifying the script to handle images with varying resolutions, backgrounds, or conditions.

## Author

* Aarti Nayak
* Github: https://github.com/aartinayak



