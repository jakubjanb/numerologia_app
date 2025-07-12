# Numerologia App

A lightweight web application for numerological calculations and analysis. This application provides various tools for numerological analysis, including name analysis, Pythagorean square generation, magic square generation, and birth date analysis.

## Features

### Numerology Calculator (Kalkulator Numerologiczny)
- Input names for numerological analysis
- Calculate Gematrikon, Nous, Psyche, and Soma values for each letter
- Display results in tables with totals and digit reduction to a single digit
- Color-code special numbers:
  - Master Numbers (green)
  - Perfect Numbers (purple)
  - Fatal/Diabolical Numbers (red)
- Generate PDF reports of the analysis

### Pythagorean Square (Kwadrat Pitagorejski)
- Generate a 3x3 numerological grid based on input names
- Place letters in cells according to their Soma value
- Provide a summary showing the distribution of letters across different numerological values
- Automatically adjust font size based on the number of letters in each cell
- Highlight completed lines and empty cells with color coding
- Generate PDF reports of the analysis

### Magic Square (Kwadrat Magiczny)
- Similar to the Pythagorean Square but with different visualization and analysis
- Generate a 3x3 grid with letters placed according to numerological principles
- Color-code cells to indicate presence or absence of letters
- Provide analysis tables for the distribution of letters
- Generate PDF reports of the analysis

### Birth Date Analysis (Analiza Daty Urodzenia)
- Calculate numerological values based on birth date (day, month, year)
- Display results in an interactive triangular chart
- Show life cycles based on numerological principles
- Visualize the reduction process for each component
- Cross-browser compatible date input with fallback options
- Generate PDF reports of the analysis

## Technologies Used

- **HTML5** - Structure and content
- **JavaScript** - Dynamic functionality and calculations
- **Tailwind CSS** - Styling and responsive design
- **SVG** - Interactive visualizations (especially in the birth date analysis)
- **Chart.js** - For generating charts and visualizations
- **jsPDF & html2canvas** - For PDF report generation

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jakubjanb/numerologia_app.git
   cd numerologia_app
   ```

2. No build process is required. The application can be run directly in a web browser.

## Usage

1. Open `index.html` in your web browser to access the main page
2. Select one of the available tools:
   - Kalkulator Numerologiczny (Numerology Calculator)
   - Kwadrat Pitagorejski (Pythagorean Square)
   - Kwadrat Magiczny (Magic Square)
   - Analiza Daty Urodzenia (Birth Date Analysis)
3. Follow the on-screen instructions for each tool:
   - For the Numerology Calculator: Enter names and click "Oblicz" (Calculate)
   - For the Pythagorean Square: Enter names and click "Generuj Kwadraty" (Generate Squares)
   - For the Magic Square: Enter names and click "Generuj Kwadraty" (Generate Squares)
   - For Birth Date Analysis: Select a date and click "Analizuj" (Analyze)
4. Use the PDF generation buttons to save your analysis as a PDF file

## Project Structure

- `index.html` - Main landing page with links to all tools
- `kalkulator_numerologiczny.html` - Numerology Calculator implementation
- `kwadrat_pitagorejski.html` - Pythagorean Square implementation
- `kwadrat_magiczny.html` - Magic Square implementation
- `analiza_daty_urodzenia.html` - Birth Date Analysis implementation
- `letterValues.json` - JSON file containing numerological values for each letter
- `specialNumbers.json` - JSON file containing special numerological numbers and their color coding
- `sth-logo.png` - Logo image used in the application
- `SGH.jpeg` - Additional image resource

## Data Files

- `letterValues.json` - Contains mappings of letters to their numerological values (Gematrikon, Nous, Psyche, and Soma)
- `specialNumbers.json` - Contains special numerological numbers categorized as:
  - Master Numbers (green)
  - Perfect Numbers (purple)
  - Fatal/Diabolical Numbers (red)

## Language

The application interface is in Polish.

## License

This project is available for personal and educational use.
