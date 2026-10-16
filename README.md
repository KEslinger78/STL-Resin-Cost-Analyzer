# STL Resin Cost Analyzer

**Free Windows software for estimating resin 3D-printing costs and approximate print times from STL files.**

[**Download the latest Windows release**](https://github.com/KEslinger78/STL-Resin-Cost-Analyzer/releases/latest)

STL Resin Cost Analyzer scans folders of models and helps you estimate resin consumption without opening each STL in a slicer.

## Features

- Batch scan folders of `.stl` files, optionally including subfolders.
- Estimate resin volume (mL), weight (g), material cost, and approximate printing time.
- Configurable resin cost, density, waste factor, slice settings, and printer time profile.
- Interactive OpenGL preview: rotate, zoom, and pan.
- Caching and parallel processing for collections of models.
- Display costs in several currencies using **manual exchange rates** (USD by default).
- Export results to an Excel-compatible CSV file.
- Optional developer tips; all functions are free.

## Screenshots

### Completed analysis and interactive 3D preview

![Completed analysis and 3D model preview](screenshots/STL-Analyzer-3.png)

### Printer, resin, and currency preferences

![Analysis and printer preferences](screenshots/STL-Analyzer-2.png)

### Main application window

![STL Resin Cost Analyzer main window](screenshots/STL-Analyzer-1.png)

## Install

1. Visit [Releases](https://github.com/KEslinger78/STL-Resin-Cost-Analyzer/releases/latest).
2. Download `STL-Resin-Cost-Analyzer-v1.0.0-win64.zip`.
3. **Extract the entire ZIP**, keeping all bundled subfolders together.
4. Run `STL Resin Cost Analyzer.exe`. Python is not required.
5. Choose the folder of STL models you want to analyze, configure Preferences, and start scanning.

**Windows SmartScreen:** This personal freeware project currently distributes an **unsigned** executable, so Windows may show an "Unknown publisher" notice. Always obtain the ZIP from this repository and check its provided SHA-256 checksum if you want to verify the download.

## Accuracy and limits

The tool estimates resin usage from model geometry. It is not a slicer and cannot predict all effects of printer settings or supports added later. Hollowed, damaged, self-intersecting, or complex meshes may give different results from CHITUBOX or Lychee. Print duration is an estimate rather than a guaranteed completion time.

**Verify important prints in your slicing application.**

## Privacy and help

Models are analyzed locally; STL files are not intentionally uploaded. Exchange rates are stored/entered locally and are not automatically fetched. No application telemetry is built in. The optional tip link opens an external Venmo page. See [Privacy](PRIVACY.md) and [Support](SUPPORT.md).

Please report bugs or suggestions through [GitHub Issues](https://github.com/KEslinger78/STL-Resin-Cost-Analyzer/issues). Do not upload third-party or private models without permission.

## License

**Freeware; source code is private.** License notices for bundled third-party libraries are provided with the Windows release in the `LEGAL` folder. The program is independently maintained by **KEslinger78**, not associated with 10th Circle.
