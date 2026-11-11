# AI Handwritten Note Digitizer 📝

A beginner-friendly OCR project that converts text from a handwritten-note image into editable digital text.

## Features

- Upload JPG, JPEG or PNG note images
- Image preprocessing using OpenCV
- OCR-based text extraction
- Edit extracted text
- Download the result as a `.txt` file
- Simple Streamlit interface

## Technologies

- Python
- Streamlit
- OpenCV
- Pillow
- Tesseract OCR
- NumPy

## Project Flow

Handwritten Note Image
→ Image Upload
→ Image Preprocessing
→ OCR
→ Digital Text
→ Edit
→ Download

## Run Locally

Install Python and Tesseract OCR, then run:

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Google Colab

The project files can be uploaded to a Colab runtime. Install the Python packages and Tesseract OCR first:

```bash
!pip install -r requirements.txt
!apt-get update -qq
!apt-get install -y tesseract-ocr
```

Then the Streamlit app can be launched using a suitable Colab tunneling setup.

## Limitations

Basic OCR systems may struggle with unclear or highly cursive handwriting. Clear images with good lighting generally work better.

## Future Improvements

- AI-based handwriting recognition
- Automatic note summarization
- MCQ generation
- Flashcard generation
- Formula and diagram extraction
- Chapter-wise note organization
