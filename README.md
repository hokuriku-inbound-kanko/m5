# m5

日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

Open data from Wi-Fi packet sensing for tourism flow analysis in the Hokuriku region, collected by Kanazawa University.

## Background
This dataset uses Wi-Fi packet sensing technology to analyze tourist behavior and movement patterns in six designated areas (area1–area6). The data supports tourism planning and infrastructure optimization by tracking temporal visitation trends. The methodology is detailed in the reference paper below.

## Data Files
The repository contains the following files:
- **CSV Data**:
  `kaiteki/area1_m5.csv` through `kaiteki/area6_m5.csv`
  These files record time-stamped counts of Wi-Fi activity. Use `00_M5_facility list.csv` to map area numbers (area1–area6) to real-world locations.
- **Web Viewer**:
  `kaiteki/index.html` provides an interactive visualization of the data using Chart.js.

## Data Columns
CSV files include the following columns:
- `year`, `month`, `day`, `hour`, `minute`, `second`: Timestamp of measurement.
- `count`: Number of detected Wi-Fi packets or devices at the specified time.

## Web Viewer
A built-in web dashboard (`kaiteki/index.html`) allows exploration of the data visually. It uses [Tailwind CSS](https://tailwindcss.com/) and [Chart.js](https://www.chartjs.org/) for responsive, browser-based analysis.

## Reference Paper
"Wi-Fi Packet Sensing for Analyzing Cruise Passenger Tourist Behavior in Kanazawa Port, Ishikawa Prefecture"
[Read the paper (J-STAGE)](https://www.jstage.jst.go.jp/article/jsceiii/1/J1/1_560/_pdf/-char/ja)

## Published By
This dataset is published by the **Hokuriku Inbound Tourism DX Data Consortium**, a collaboration focused on digital transformation in regional tourism.

## License
MIT License. See [LICENSE](LICENSE) for details.
