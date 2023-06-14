# LabelOCR

<!-- Install these libraries in the current directory:

pip install virtualenv

pip install pytesseract

pip install opencv-python
 -->
 
This repository contains a project that focuses on extracting product information from images using Optical Character Recognition (OCR) techniques. The goal is to process images containing product labels, packaging, or other relevant information and extract key details such as product type, directions, supplements/ingredients, and warnings.

The project utilizes a combination of computer vision techniques, deep learning models (CNN and RNN), and natural language processing (NLP) to perform image processing, text extraction, and data classification. It leverages the Tesseract OCR engine, PyTorch deep learning framework, Open Food Facts API, and various Python libraries for image manipulation and data processing.

<br/>

<h3 align="center">Class Diagram</h3>
<img align="center" src="https://github.com/hseitaj/LabelOCR/blob/CMPSC/Diagrams/Label%20OCR%20-%20Study%20Diagram%20-%20Work%20Flow.jpg">

## Key Features

- Image preprocessing and enhancement techniques for optimal OCR results.
- Convolutional Neural Network (CNN) for image feature extraction.
- Recurrent Neural Network (RNN) for sequence recognition and classification.
- Integration of CNN and RNN into a CRNN model for joint image and text analysis.
- Multithreaded image processing for improved efficiency.
- Data extraction based on predefined keywords and text matching.
- Integration with Open Food Facts API for retrieving additional product information.
- Visualization and analysis of extracted data using Pandas DataFrames.

## Usage

To use this project, follow these steps:

1. Install the required dependencies listed in the `requirements.txt` file.
2. Set up Tesseract OCR and ensure the path to the Tesseract executable is correctly configured.
3. Prepare a folder containing the images you want to process and set the folder path in the `folder_path` variable.
4. Run the `folderOCR(folder_path)` function to process the images and extract the product information.
5. The extracted data will be saved as a JSON file and a CSV file in the `folder_path_after` directory.
6. You can also explore and analyze the extracted data using the provided Pandas DataFrames.


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

This project was developed as part of the Summer MCREU program at Penn State University. We would like to thank the mentors and advisors for their guidance and support throughout the project.

Special thanks to the developers and contributors of the open-source libraries and frameworks used in this project.

<!-- 
Notes for me, to add later on.
- [Project Report](https://github.com/hseitaj/Interactive-Flow-Chart/blob/CMPSC/Additional%20Files/CMPSC%20487w%20-%20Final%20Report.pdf)
- [Demo](https://psu.mediaspace.kaltura.com/media/Hansi+Seitaj%27s+Zoom+Meeting/1_41j4889b?st=0&ed=285)

<br />
 -->

