# AI-Powered Landscape Change Detection

## Overview

This project implements an AI-powered solution for detecting landscape changes using satellite imagery. It leverages a U-Net deep learning model, Gemini AI for analysis, and a Streamlit web interface for user interaction. The application allows users to upload "before" and "after" images, process them using the U-Net model, visualize the detected changes, and generate comprehensive PDF reports.

## Key Features

*   **U-Net Model:** Employs a U-Net deep learning model for accurate image segmentation and change detection.
*   **Gemini AI Integration:** Integrates with Google's Gemini AI for intelligent analysis and insights into detected changes.
*   **Streamlit Interface:** Provides an intuitive web interface for easy interaction and visualization.
*   **Image Preprocessing:** Uses Albumentations for image augmentation and preprocessing to improve model performance.
*   **PDF Report Generation:** Generates detailed PDF reports including before/after images, AI analysis, and evaluation metrics.
*   **Interactive Visualization:** Offers interactive visualizations of the detected changes and model performance metrics.
*   **Multi-Language Support:** Provides multi-language support for AI analysis using the `googletrans` library.

## Technologies Used

*   Python
*   Streamlit
*   PyTorch
*   Albumentations
*   Google Generative AI
*   PIL (Pillow)
*   fpdf
*   streamlit\_image\_comparison
*   streamlit\_drawable\_canvas
*   googletrans
*   imgaug
*   pandas
*   plotly
*   numpy

## Setup and Installation

1.  **Clone the repository:**

    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python -m venv venv
    venv\Scripts\activate  # On Windows
    source venv/bin/activate   # On macOS and Linux
    ```

3.  **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Set up the environment variables:**

    *   Create a `.env` file in the project directory.
    *   Add your Gemini API key to the `.env` file:

        ```
        GEMINI_API_KEY=YOUR_GEMINI_API_KEY
        ```

## Usage

1.  **Run the Streamlit application:**

    ```bash
    streamlit run app.py
    ```

2.  **Open the application in your browser:**

    *   The application will typically be available at `http://localhost:8501`.

3.  **Upload Images:**

    *   Upload a "before" image and an "after" image using the file uploaders.

4.  **Run Change Detection:**

    *   Click the "Submit" button to process the images and detect changes.

5.  **View Results:**

    *   The application will display the predicted change mask and the original images with the detected changes highlighted.

6.  **AI Analysis:**

    *   Use the Gemini AI analysis section in the sidebar to ask questions and gain insights about the detected changes.

7.  **Generate Report:**

    *   Click the "Generate Report" button to create a PDF report summarizing the analysis.

## Model Training

*(Note: This section assumes you have training data and a trained model. If not, you'll need to create/obtain these.)*

1.  **Prepare Training Data:**

    *   Organize your training data into appropriate directories.
    *   Ensure the data is preprocessed and augmented as needed.

2.  **Train the U-Net Model:**

    *   Modify the `predict.py` script to load your trained model.
    *   Adjust the script to correctly process your input data.

## Contributing

Contributions to this project are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Implement your changes.
4.  Test your changes thoroughly.
5.  Submit a pull request.


## Contact

*   Tafazzul Hazqueel Syed - tasy23@student.bth.se
*   Dr. Huseyin Kusetogullari - huseyin.kusetogullari@bth.se



#   A I - P o w e r e d - L a n d s c a p e - C h a n g e - D e t e c t i o n  
 