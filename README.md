GPSJam KML Builder
What changed in v3.1.3: Removed the redundant in-app menu bar. The non-functional File, Tools and Help labels have been removed rather than left as decorative controls. The normal Windows title bar still provides the application title and window controls.
More room for the dashboard. Removing the pseudo menu/title strip returns roughly 42 pixels of vertical space to the map preview and KML panels.
Retained controls. The custom region selector, custom UTC calendar, native Windows Save As dialogue, self-contained map renderer and Pallas branding remain in place.

Build the EXE:
Extract the ZIP and double-click:

build_exe_windows.bat

The generated executable will be here:

dist\GPSJam KML Builder v3.1.3.exe

The build script creates a local virtual environment, installs the dependencies and builds a standalone EXE. The finished EXE does not need Python installed.

Runtime requirements
Internet access for GPSJam data and online map tiles.
Microsoft Edge WebView2 Runtime, normally already installed on current Windows 10/11 systems.

Data caveat
GPSJam represents aggregated ADS-B aircraft reports of low navigation accuracy by H3 hexagon within a 24-hour UTC window. It can highlight areas consistent with potential GNSS disruption, but it does not locate a transmitter or establish the cause of degraded navigation accuracy.
