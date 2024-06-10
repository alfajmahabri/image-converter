# Image Converter

## Overview
The Image Converter project is a Java-based desktop application that allows users to convert images from various formats to JPEG, PNG, GIF, BMP, and PDF. Users can either provide an image URL or select files from their device to convert.

## Features
- Converts images from Local & URL
- Built using Java
- Multiple file selection
- User Friendly GUI
- Supported Formats :- JPEG , PNG, GIF, BMP & PDF

## Requirements
- Java Development Kit (JDK) 8 or higher
- Apache PDFBOX Library 

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/alfajmahabri/image-converter.git
   ```
2. Navigate to the project directory:
   ```bash
   cd image-converter
   ```
3. Download the dependencies:
   ```xml
   <!-- Add this to your pom.xml -->
   <dependency>
       <groupId>org.apache.pdfbox</groupId>
       <artifactId>pdfbox</artifactId>
       <version>2.0.24</version>
   </dependency>
   ```


## File Structure

```
image-converter/
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── example/
│                   └── MainGUI.java
├── target/
├── README.md
└── pom.xml
```

  
## Note
Before creation of dependency download dependencies of PDFBox.Apache from https://pdfbox.apache.org/2.0/dependencies.html

## License
This project is licensed under the MIT License.
