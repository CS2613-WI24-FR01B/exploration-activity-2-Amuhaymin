# NBA Statistics Visualization Tool

This sample program demonstrates the use of Node.js with the Express framework, along with client-side technologies including HTML, the C3.js charting library, D3.js for data manipulation, and Papa Parse for parsing CSV data.

## 1. Package/Library Demonstrated

This program is built using:

- **Node.js and Express**: for creating the web server.
- **C3.js and D3.js**: for generating interactive charts.
- **Papa Parse**: for parsing CSV files in the browser.

## 2. How to Run the Program

Ensure you have Node.js installed on your computer. Follow these steps to run the program:

1. Install Express and other Node.js dependencies (if any). Open a terminal and run:

```bash
npm install express
```

2. Clone this repository to your local machine:

```bash
git clone <https://github.com/CS2613-WI24-FR01B/exploration-activity-2-Amuhaymin>
```

3. Navigate to the project directory:

```bash
cd <exploration-activity-2-Amuhaymin>
```

4. Run the server using Node.js:

```bash
node app.js
```

Or, if you've set up a script in your `package.json`, you might use:

```bash
npm start
```

Ensure all files, especially the HTML and CSV data file (`nba2021_advanced.csv`), are in the `public` directory or correctly referenced in your project.

## 3. Purpose of the Program

The purpose of this program is to visualize NBA player statistics on a web page using interactive charts. By leveraging the combined power of C3.js, D3.js, and Papa Parse, it parses NBA statistics from a CSV file and presents the data in a user-friendly bar chart format, allowing users to explore trends such as average Beats Per Minute (BPM) and Turnover Percentage (TOV%) across different player positions.

## 4. Sample Input/Output

- **Input**: The program reads NBA player statistics from a CSV file.
- **Output**: It displays an interactive bar chart visualizing average player BPM and TOV% by position.

## 5. References and Resources Used

- Node.js and Express documentation for server setup.
- C3.js [documentation](https://c3js.org/) for chart creation.
- D3.js [API Reference](https://github.com/d3/d3/blob/master/API.md) for data manipulation.
- Papa Parse [documentation](https://www.papaparse.com/) for parsing CSV files.
