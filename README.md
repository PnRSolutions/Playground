# PdfPig - Get PDF Metadata and Render the 1st Page as an Image

## Purpose

This is a minimal project designed to demonstrate how to extract metadata from a PDF file and render its first page as an image. The project is built using .NET MAUI and is intended to run on both Windows and MacCatalyst platforms.

## Libraries Used

The project utilizes the following libraries:

- **PdfPig** (Version 0.1.10): For extracting metadata from PDF files.
- **PdfPig.Rendering.Skia** (Version 0.1.10.2): For rendering PDF pages using SkiaSharp.
- **SkiaSharp** (Version 3.116.1): A 2D graphics library used for rendering the PDF page as an image.

## Platform Compatibility

- **Windows**: The project works well and performs as expected.
- **MacCatalyst**: The project throws an exception related to the font finder when attempting to render the PDF page.

## Code Structure

All the important code for this project is located in the following Razor component/page:
`PdfRender/Components/Pages/Home.razor`
