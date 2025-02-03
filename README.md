# NBA Player Stats Explorer

This app performs simple web scraping of NBA player stats data from [Basketball-reference.com](https://www.basketball-reference.com/).

## Features
- **User Input Features**: Select a year, team, and position to filter player stats.
- **Data Display**: Display filtered player stats in a table.
- **Download Data**: Download the filtered data as a CSV file.
- **Heatmap**: Generate an intercorrelation heatmap for the selected data.

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/dency-claris/EDA-Basketball.git
   ```
2. Navigate to the project directory:
   ```bash
   cd EDA-Basketball
   ```
3. Build and run the Docker container:
   ```bash
   docker build -t basketball-app .
   docker run -p 8501:8501 basketball-app
   ```
4. Open your browser and go to http://localhost:8501.

