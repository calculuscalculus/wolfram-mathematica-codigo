# wolfram-mathematica-codigo
Web Scraping Internet Archive Books Using Mathematica

## New Features: Image Description and Analysis

This notebook now includes advanced image analysis capabilities for the scraped book pages:

### Image Description Functions

- **`describeImage[imagePath]`** - Analyzes a single image and provides:
  - OCR text extraction
  - Image dimensions and properties
  - Word and line count statistics
  - Comprehensive description report

- **`batchDescribeImages[directory]`** - Processes all images in a directory and generates a summary report

- **`funcWithDescription[lista]`** - Enhanced version of the original capture function that automatically analyzes each captured page

### Features Added

1. **Optical Character Recognition (OCR)** - Extracts text content from book pages
2. **Image Analysis** - Provides technical details about images (dimensions, color space, etc.)
3. **Content Statistics** - Counts words, lines, and other text metrics
4. **Batch Processing** - Analyzes multiple images automatically
5. **Report Generation** - Creates comprehensive analysis reports in text format

### Usage

The enhanced workflow now captures book pages AND automatically describes their content, making it easier to search and catalog the extracted information.
