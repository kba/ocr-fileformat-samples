# ocr-fileformat-samples
Samples for common OCR file formats (hOCR, ABBYY, ALTO)

## Why

This repository contains sample files for common OCR file formats in a
standardized directory layout to make it easier for tools to test.

This is a sister project to
[ocr-fileformat](/UB-Mannheim/ocr-fileformat) which contains code for
format validation and inter-format transformation.

## Code organization

Samples are placed in `./samples/<format>/<format-version>/<sample>`.

Metadata about a sample is in
`./samples/<format>/<format-version>/<sample>.yml`. Metadata is
described as a YAML document with the following keys:

* **`engine`**: Engine that created this document
* **`page-side`**: `left` or `right`
* `view-url`: URL to the landing page
* `page-number`: Numeric page number
