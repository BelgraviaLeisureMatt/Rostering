# Aquatic Day Sheet Builder

A browser-based roster tool for turning a Working Day Sheet export into a weekly aquatic operations day sheet.

## Run locally

Open `index.html` in a browser, or serve this folder with a local static server:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`. Spreadsheet import and Excel export use XLSX and ExcelJS from jsDelivr, so an internet connection is required.

## Use

1. Upload a `.xlsx`, `.xls`, `.xlsm`, or `.csv` Working Day Sheet export.
2. Choose a week and day to view the generated roster.
3. Click a shift to cycle its role; double-click to edit its label. Tasks, counts, bookings, observations, aliases, and staff rules can also be edited.
4. Use **Print / PDF** for a printable weekly view or **Download Day Sheet (.xlsx)** to export the selected week.

Edits and staff display preferences are saved in the current browser using local storage. No roster data is sent to an application server.
