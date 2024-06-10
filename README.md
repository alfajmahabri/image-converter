# Image Converter

## Overview
This project is an image converter implemented in Java. It allows users to convert images from one format to another.

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
   git clone https://github.com/atharv0825/Image-Converter-java.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Image-Converter-java
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
Image-Converter-java/
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
