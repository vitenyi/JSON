# sharepoint-column-formatting

This folder contains JSON column formatting for SharePoint.

## date-year-month-day.json

Formats a SharePoint Date column to show the Year (bold) on the first line and the Month name + day on the second line. Empty/zero dates are hidden.

Usage
- Place the JSON in your column formatting settings for a Date column.
- The JSON file follows SharePoint column formatting schema v2; additional top-level properties may be ignored by SharePoint.

Notes
- GitHub shows this README when browsing this folder so it's a good place for file-level, human-readable descriptions.
- JSON itself doesn't support comments — use this README for documentation or add a top-level `description` property if your consumer supports it.
