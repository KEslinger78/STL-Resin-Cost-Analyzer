# STL Resin Cost Analyzer

**Free Windows desktop utility for estimating resin-printing costs from STL files.**

STL Resin Cost Analyzer scans a folder of STL models and produces a cost report without requiring you to open and slice every file individually.

> **Release status:** Preparing the first public Windows download. Visit [Releases](https://github.com/KEslinger78/STL-Resin-Cost-Analyzer/releases) for published builds when available.

## Features

- Analyze all `.stl` files in a selected folder; optionally include subfolders.
- Estimate resin volume (mL), resin weight (g), material cost and approximate print time.
- Slice-based volume estimation for complex or pre-supported STL geometry.
- Configurable resin price, density, waste allowance, layer settings and time profile.
- Local cache for unchanged models, with parallel processing for multiple STL files.
- Interactive OpenGL preview: rotate, zoom, pan and reset camera.
- Multi-currency display with **manual exchange rates** (USD by default).
- Excel-compatible CSV export.
- Optional developer tip link. All core features are free; no payment required.

## Download and use

1. Download the latest **Windows** ZIP under [Releases](https://github.com/KEslinger78/STL-Resin-Cost-Analyzer/releases) when available.
2. Extract the ZIP completely.
3. Run `STL Resin Cost Analyzer.exe` from the extracted folder.
4. Click **Browse**, select your STL folder, adjust **Preferences**, and click **Start Scan**.
5. Review the estimates or use **Export CSV**.

The final release ZIP may contain support DLLs and subfolders that must remain beside the EXE. You do **not** need to install Python to run an official release build.

## Accuracy and limitations

This utility estimates volumes from STL geometry rather than executing CHITUBOX or Lychee. Pre-supported STL supports already part of the model are included. Supports added later in a slicer, printer-specific corrections and print settings may change actual consumption. Hollow, intersecting and damaged meshes can also affect results. Print-time estimates are approximate and depend on printer and exposure/motion settings.

**Always check important prints in your slicer.**

## Privacy

STL analysis and CSV export happen locally. Exchange rates are entered manually; no background currency service is contacted. No telemetry or upload of STL files is built into the app. Selecting the optional tip link opens a third-party payment site. See [Privacy](PRIVACY.md).

## Support and feedback

Please use [GitHub Issues](https://github.com/KEslinger78/STL-Resin-Cost-Analyzer/issues) for bugs and feature requests. Include your Windows version, app version, and a description of the problem, but **do not post private or commercially licensed STL files** unless you have permission.

## License

STL Resin Cost Analyzer is **freeware, not open source**. The application source is privately maintained. Binary use and distribution terms will accompany published releases. Bundled third-party components retain their own licenses and user rights.

Maintained independently by **KEslinger78**.
