# Robot 4: Scanned Receipts OCR

## Overview

**Scanned Receipts OCR** is an intermediate-level RPA project built with
UiPath. It demonstrates how to extract data from scanned images that do
not contain readable UI elements, using gas station receipts as the
example.

The workflow downloads receipt images from a Google Drive folder,
processes each file, extracts text with Optical Character Recognition
(OCR), and uses Regular Expressions (Regex) to capture the required
fields. The extracted information is saved into `.txt` files.

## Workflow

1.  Download scanned receipts from a Google Drive folder.
2.  Loop through the receipt files in the folder.
3.  Extract text from each image using OCR.
4.  Use Regex patterns to identify the required fields.
5.  Save the extracted data into text files.
6.  Publish the automation to UiPath Orchestrator.
7.  Run it as an attended automation through UiPath Assistant.

## Technologies Used

-   UiPath Studio
-   Optical Character Recognition (OCR)
-   Regular Expressions (Regex)
-   Google Drive
-   UiPath Orchestrator
-   UiPath Assistant

## Key Learning Outcomes

-   Working with files that do not expose UI elements for standard data
    extraction.
-   Processing multiple image files in a loop.
-   Extracting text from scanned documents with OCR.
-   Using Regex to identify and capture specific data fields.
-   Publishing and running an attended automation with UiPath.

## Demo

A demo video is available in the project portfolio.

## Project Portfolio

[View the project
portfolio](https://www.notion.so/p/Shaik-Mustaq-s-UiPath-Project-Portfolio-37c6bf78bd76838a8d9e01defb6a0288)

## Repository

[Robot 4: Scanned Receipts OCR on
GitHub](https://github.com/Shaik-Mustaq/Robot-4-Scanned-Receipts-OCR)

## Author

**Shaik Mustaq**

This project was built without coding-agent assistance to strengthen my
UiPath RPA fundamentals and problem-solving skills.
