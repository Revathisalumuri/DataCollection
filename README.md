## Financial Data Collection Tool

A professional Qt-based desktop application for extracting financial data from PDF documents.

## Features

- **PDF Document Processing**: Load and view PDF financial reports
- **Automated Data Extraction**: Extract revenue, expenses, and asset data
- **Real-time Processing Logs**: Monitor extraction progress with detailed logs
- **Multiple Export Formats**: Export data as JSON, CSV, or Excel
- **Professional UI**: Modern, intuitive interface with organized data panels
- **Data Validation**: Built-in validation for extracted financial data

## Project Structure

```
FinancialDataTool/
├── main.cpp              # Application entry point
├── mainwindow.h          # Main window header
├── mainwindow.cpp        # Main window implementation
├── mainwindow.ui         # Qt Designer UI file
├── CMakeLists.txt        # CMake build configuration
├── FinancialDataTool.pro # qmake project file
└── README.md            # This file
```

## Building the Application

### Using Qt Creator

1. Open `FinancialDataTool.pro` in Qt Creator
2. Configure the project with your Qt kit
3. Build and run the application

### Using CMake

```bash
mkdir build
cd build
cmake ..
make
```

### Using qmake

```bash
qmake FinancialDataTool.pro
make
```

## Requirements

- Qt 6.0 or later
- C++17 compatible compiler
- CMake 3.16+ (if using CMake build)

## Usage

1. **Upload PDF**: Click "Upload PDF" or use File → Open PDF to load a financial document
2. **Process**: Click "Process" or press F5 to extract financial data
3. **Monitor**: Watch the processing logs for real-time status updates
4. **Review**: Check extracted data in the right panel
5. **Export**: Use the Export menu to save data in your preferred format
6. **Validate**: Use Tools → Validate Data to check data consistency

## UI Components

- **Menu Bar**: Complete menu system with File, Edit, View, Process, Export, Tools, and Help
- **Toolbar**: Quick access buttons for common operations
- **PDF Viewer**: Central panel for PDF document preview
- **Data Panel**: Right sidebar showing extracted financial data organized by category
- **Processing Logs**: Bottom panel with real-time processing status and logs
- **Status Bar**: Application status and progress indicator

## Data Categories

The application extracts and organizes data into three main categories:

1. **Revenue Data**
   - Total Revenue
   - Q4 Revenue

2. **Expenses**
   - Operating Expenses
   - Marketing Expenses

3. **Assets & Liabilities**
   - Total Assets
   - Current Liabilities

## Keyboard Shortcuts

- `Ctrl+O`: Open PDF
- `Ctrl+U`: Upload PDF
- `F5`: Process PDF
- `Ctrl+E`: Export Data
- `Ctrl+Q`: Exit Application
- `Ctrl+=`: Zoom In
- `Ctrl+-`: Zoom Out

## License

This project is provided as-is for educational and development purposes.
