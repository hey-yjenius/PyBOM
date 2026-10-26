# Getting started

## Download

Download **[PyBOM-Windows-x64.zip](https://github.com/hey-yjenius/PyBOM/releases/latest/download/PyBOM-Windows-x64.zip)** from the latest release.

Choose the Windows ZIP, not GitHub's automatic **Source code** downloads. The source downloads are not the application.

## Open the application

1. Right-click the ZIP and choose **Extract All**.
2. Open the extracted `PyBOM` folder.
3. Double-click **PyBOM.exe**.

Keep `_internal` and the other supplied files next to the executable. Moving only `PyBOM.exe` will not work.

The package targets 64-bit Windows. It does not require Python or administrator installation. This release was checked on Windows 11; other Windows versions have not been separately verified.

The executable is not code-signed. Windows or your organization's security tools may warn about it. Follow your organization's software approval process; do not disable security controls.

## Try the example first

Download the **[English example](https://github.com/hey-yjenius/PyBOM/releases/latest/download/PyBOM-Example-EN.xlsx)** or **[Korean example](https://github.com/hey-yjenius/PyBOM/releases/latest/download/PyBOM-Example.xlsx)**. The Windows ZIP includes the original Korean example; the English edition is a separate download.

1. Choose **File > Open**, or press **Ctrl+O**.
2. Open the downloaded `PyBOM-Example-EN.xlsx`, or `PyBOM-Example.xlsx` from the extracted folder.
3. Review the sheet and column mapping.
4. Review the import summary and choose **Run all**.
5. Start with the dashboard, then open the MRP and Coverage tabs.

The example contains fictional demonstration data, not a production plan.

In the English edition, start with **Read me** and hover over column headers for explanations and input rules. Use the as-of date **2026-10-15** to reproduce the example's schedule; a different date changes time-sensitive results.

## Prepare your own data

Use the **[data preparation guide](guides/DATA_PREPARATION.md)** to match the workbook structure. The application also includes an offline Korean field guide under **Help > Field Guide**.

For useful material planning, supply your BOM, item master, inventory and dated demand. Optional supplier, receipt and cost information improves the corresponding analysis. Review every missing-data warning rather than treating a partial result as complete.

## Save results

Use **File > Export All** for the analysis workbook. Use the Manager Brief for a concise summary. Exported recommendations are advisory and do not update your ERP.

## Update

Close PyBOM, extract the new release to a new folder and open its executable. Keep input workbooks and exports outside the application folder. Do not mix `_internal` files from different releases.

## Troubleshooting

- **The app does not open:** confirm that the ZIP was fully extracted and `_internal` is present.
- **Your file does not import:** read the error details and check the sheet names and required columns against the guide.
- **A number looks incomplete:** check the import summary and the result's missing-data disclosures.
- **Need help:** follow the [support instructions](SUPPORT.md). Do not attach confidential business data.

[Back to PyBOM](README.md)
