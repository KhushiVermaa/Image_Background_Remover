# Image Background Remover

### Project Overview
This is a simple tool built using Python and Streamlit for removing the background from images. It utilizes a pre-trained model deployed on a remote server to perform the background removal task. Users can upload an image, select a point on the image that represents the background they want to remove, and then the tool will process the image and display the result with the background removed.

### Project Output
The output is in the form of webpage which is designed using streamlit module.

<img width="1440" alt="Screenshot 2024-04-14 at 11 12 36 PM" src="https://github.com/KhushiVermaa/Image_Background_Remover/assets/161287265/211fdaae-855d-4f88-8126-ecd03748df45">

### Usage
1. Upload Image: Click on the file uploader and select an image file (supported formats: JPEG, JPG, PNG).
2. Select Background Point: Once the image is uploaded, click on the image to select a point that represents the background you want to remove.
3. Remove Background: After selecting the background point, click on the "Remove background" button. The tool will process the image and display the result with the background removed.

### Tools and libraries used
- Tools - Google Colab, PyCharm, Streamlit
- Libraries - numpy, pandas, streamlit, base64, os, requests, streamlit, PIL (Python Imaging Library), opencv-python, streamlit_image_coordinates

### Output 

<img width="1440" alt="Screenshot 2024-04-14 at 11 29 59 PM" src="https://github.com/KhushiVermaa/Image_Background_Remover/assets/161287265/460ff3f0-5d43-4d4c-8a3b-74baf838b9b5">


- Click on the image to select on a point which is not to be removed.
  
<img width="1440" alt="Screenshot 2024-04-14 at 11 48 07 PM" src="https://github.com/KhushiVermaa/Image_Background_Remover/assets/161287265/0a5d6412-9488-4814-bd6d-2e9d780a0a09">


### How to run the project ?
- Make sure to write own API endpoint.
- Open the python file and run streamlit command in the terminal.
- streamlit run <file_name.py>
