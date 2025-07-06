# Image Information Extractor

A web application that extracts addresses and codes from images using OCR (Optical Character Recognition) technology.

## Features

- **Drag & Drop Upload**: Simply drag images into the upload zone or click to browse
- **Multiple Format Support**: Supports JPEG, PNG, GIF, BMP, TIFF, and PDF files
- **OCR Processing**: Uses Tesseract.js to extract text from images
- **Smart Pattern Matching**: Automatically identifies addresses and codes (6+ digits)
- **Progress Tracking**: Real-time progress bar during processing
- **Results Table**: Displays extracted information in an organized table
- **Modern UI**: Responsive design with beautiful animations

## How to Use

1. **Open the Application**: Open `index.html` in your web browser
2. **Load Images**: 
   - Drag and drop images into the upload zone, or
   - Click "Load Images" to browse and select files
3. **Process Images**: Click "Process Images" to start OCR extraction
4. **View Results**: Check the results table for extracted addresses and codes
5. **Clear All**: Use "Clear All" to reset and start over

## What Information is Extracted

- **Addresses**: Street addresses, city/state/ZIP combinations, and location information
- **Codes**: Numeric codes with 6 or more digits (commonly found in boarding passes, tickets, etc.)

## Technical Details

- **OCR Engine**: Tesseract.js v4.1.1
- **Languages**: English text recognition
- **Processing**: Client-side processing (no data sent to servers)
- **Compatibility**: Works in all modern web browsers

## File Structure

```
index.html          # Main application file
README.md          # This documentation file
```

## Browser Requirements

- Modern web browser with JavaScript enabled
- Internet connection (for loading Tesseract.js library)

## Usage Tips

- **Image Quality**: Higher quality images produce better OCR results
- **Text Clarity**: Ensure text is clear and not blurry or distorted
- **Lighting**: Good lighting and contrast improve extraction accuracy
- **File Size**: Large images may take longer to process

## Processing Time

Processing time varies based on:
- Image size and complexity
- Text density
- Device performance
- Network speed (for library loading)

The application shows real-time progress and processing times for each image.
