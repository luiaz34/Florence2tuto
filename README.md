# Florence2tuto

This is a demo of how to use Florence2 for image processing and live video streaming.

## How to set up

1. Install the required packages:
    ```sh
    !pip install accelerate flash_attn einops timm
    ```

2. Upload your desired photo.

3. Update the code with the name of your image:
    ```python
    from PIL import Image
    
    img1 = Image.open('yourImage.jpg')
    img2 = Image.open('yourImage.jpg')
    img3 = Image.open('yourImage.jpg')
    ```

4. Integrate with live video streaming:
    - Run the cell and click the capture button to see the results.

## Usage

1. Ensure you have the necessary packages installed as mentioned in the setup.
2. Upload the image you want to process.
3. Replace `'yourImage.jpg'` with the name of your uploaded image in the code.
4. Run the live video streaming integration to see the processed results.

Enjoy experimenting with Florence2!
