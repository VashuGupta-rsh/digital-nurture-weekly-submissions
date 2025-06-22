# FactoryMethodPatternExample

This project demonstrates the **Factory Method Design Pattern** in Java

The program simulates a **document management system** that creates different types of documents (Word, PDF, Excel) using the factory method approach.

## Files

- `Document.java` – Interface representing a generic document.
- `WordDocument.java` – Concrete implementation for Word documents.
- `PdfDocument.java` – Concrete implementation for PDF documents.
- `ExcelDocument.java` – Concrete implementation for Excel documents.
- `DocumentFactory.java` – Abstract factory class defining the `createDocument()` method.
- `WordDocumentFactory.java` – Factory class to create Word documents.
- `PdfDocumentFactory.java` – Factory class to create PDF documents.
- `ExcelDocumentFactory.java` – Factory class to create Excel documents.
- `TestFactoryMethod.