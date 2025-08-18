# wolfram-mathematica-codigo
Web Scraping Internet Archive Books Using Mathematica

## Features

- Scrapes books from Internet Archive
- Captures page screenshots 
- Processes images by extracting specific sections
- **NEW**: Extracts image metadata (size, format, resolution, file size)
- **NEW**: Generates CSV report with metadata for each processed image

## Image Metadata Analysis

The enhanced scraping workflow now includes automatic analysis of downloaded images with the following metadata extraction:

- **Width and Height**: Image dimensions in pixels
- **Type**: Image format/type
- **Resolution**: Image resolution
- **File Size**: Size of the image in bytes
- **Status**: Processing status (Success/Failed)
- **Page**: Source page number
- **Image Type**: Position indicator (Left/Right page)

### Output

The system generates a `book_images_metadata.csv` file containing:
- One row per processed image
- All metadata fields as columns
- Status tracking for successful/failed processing

### Functions Added

- `extractImageMetadata[image]`: Extracts metadata from an image object
- Enhanced `func[lista]`: Main scraping function now collects and exports metadata
