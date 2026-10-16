# Privacy notice

This document describes the v8 app architecture intended for the first public release.

- **Models:** User-selected STL files are read on the local computer. The application does not upload model files to a server.
- **Local data:** App preferences are stored on the local computer under `%APPDATA%\STL Resin Cost Analyzer`. Cache and JIT artifacts are stored under `%LOCALAPPDATA%\STL Resin Cost Analyzer` where supported. Cost reports are exported to a locally chosen CSV file.
- **Internet access:** The application does not fetch live foreign exchange rates or send telemetry. Opening the optional Venmo tip link deliberately launches the external site/browser, which then has its own privacy practices.
- **Payments:** The application does not collect card or bank credentials and does not process payment transactions.
- **GitHub:** If you file a GitHub Issue or download a release, GitHub processes that interaction according to GitHub's policies.

This policy should be rechecked against the final compiled release before publication and updated if the app's behavior changes.
