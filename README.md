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
    

## Usage

1. Clone or Download the Repository: Clone the repository containing the MATLAB script to your local machine or download it as a ZIP file and extract its contents.

```python
def hello_world():
    print("Hello, World!")

hello_world()
<pre>
<code class="language-python">
def hello_world():
    print("Hello, World!")

hello_world()
</code>
</pre>
<button class="copy-button" data-clipboard-target="#code-snippet">Copy</button>
<script>
    var clipboard = new ClipboardJS('.copy-button');

    clipboard.on('success', function(e) {
        e.clearSelection();
    });
</script>
<style>
    pre {
        background-color: #f4f4f4;
        padding: 10px;
        border: 1px solid #ddd;
        border-radius: 5px;
    }
    button.copy-button {
        background-color: #007acc;
        color: #fff;
        border: none;
        border-radius: 5px;
        padding: 5px 10px;
        cursor: pointer;
    }
</style>


Prepare Input Images: Place your input image files in the same directory as the script. Alternatively, you can specify the file paths within the script.

Run the Script: Open MATLAB and navigate to the directory containing the script. Run the script by typing the following command in the MATLAB command window, replacing 'your_image.jpg' with the path to your input image file:

