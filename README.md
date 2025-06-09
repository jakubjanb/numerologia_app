# Numerologia App

A lightweight web application for numerological calculations and analysis. This application provides various tools for numerological analysis, including name analysis, magic square generation, and birth date analysis.

## Features

### Numerology Calculator (Kalkulator Numerologiczny)
- Input up to 5 names separated by spaces
- Calculate Gematrikon, Nous, Psyche, and Soma values for each letter
- Display results in tables with totals and digit reduction to a single digit
- Color-code special numbers:
  - Master Numbers (green)
  - Perfect Numbers (purple)
  - Fatal/Diabolical Numbers (red)

### Magic Square (Kwadrat Magiczny)
- Generate a 3x3 numerological grid based on input names
- Place letters in cells according to their Soma value
- Provide a summary showing the distribution of letters across different numerological values
- Automatically adjust font size based on the number of letters in each cell

### Birth Date Analysis (Analiza Daty Urodzenia)
- Calculate numerological values based on birth date (day, month, year)
- Display results in an interactive triangular chart
- Show life cycles based on numerological principles
- Visualize the reduction process for each component

## Technologies Used

- **HTML5** - Structure and content
- **JavaScript** - Dynamic functionality and calculations
- **Tailwind CSS** - Styling and responsive design
- **SVG** - Interactive visualizations (especially in the birth date analysis)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jakubjanb/numerologia_app.git
   cd numerologia_app
   ```

2. No build process is required. The application can be run directly in a web browser.

## Usage

1. Open `numerologia.html` in your web browser to access the main page
2. Select one of the available tools:
   - Kalkulator Numerologiczny (Numerology Calculator)
   - Kwadrat Magiczny (Magic Square)
   - Analiza Daty Urodzenia (Birth Date Analysis)
3. Follow the on-screen instructions for each tool:
   - For the Numerology Calculator: Enter names and click "Oblicz" (Calculate)
   - For the Magic Square: Enter names and click "Generuj Kwadraty" (Generate Squares)
   - For Birth Date Analysis: Select a date and click "Analizuj" (Analyze)

## Project Structure

- `numerologia.html` - Main landing page with links to all tools
- `index.html` - Numerology Calculator implementation
- `kwadrat_magiczny.html` - Magic Square implementation
- `analiza_daty_urodzenia.html` - Birth Date Analysis implementation
- `sth-logo.png` - Logo image used in the application
- `SGH.jpeg` - Additional image resource

## Language

The application interface is in Polish.

## License

This project is available for personal and educational use.


