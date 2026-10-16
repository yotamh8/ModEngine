# Third-party notices

ModEngine 1.0.0 includes the open-source components below. Each is used under its own license; those licenses
take precedence over the ModEngine License for that component. The full license texts are in
`THIRD_PARTY_LICENSES.txt`, shipped next to ModEngine.

| Component | Used for | License |
|---|---|---|
| Python 3.12 (CPython runtime and standard library) | runs ModEngine | PSF License Agreement |
| pywebview 5.4 | the app window | BSD 3-Clause |
| pythonnet 3.0 and clr-loader 0.2 | talking to Windows' WebView2 control | MIT |
| bottle 0.13 | serving the app page inside the window | MIT |
| proxy_tools 0.1 | used by pywebview | MIT |
| typing_extensions | used by pywebview | PSF License |
| Pillow 10.4 | game icons and the app logo | MIT-CMU (HPND) |
| NumPy 2.4 (with OpenBLAS and other bundled libraries) | fast memory scanning | BSD 3-Clause, and the licenses of its bundled libraries |
| cffi and pycparser | used by the libraries above | MIT, BSD 3-Clause |
| PyInstaller bootloader 6.22 | starting the packaged exe | GPL 2.0 with the PyInstaller bootloader exception, which allows use in any program |
| Microsoft Visual C++ Runtime (vcruntime140.dll) | required by Python | Microsoft Visual C++ Redistributable license |
| Inter font (The Inter Project Authors) | the app's text | SIL Open Font License 1.1 |
| Outfit font (The Outfit Project Authors) | the app's headings | SIL Open Font License 1.1 |

Not included, used from Windows: **Microsoft Edge WebView2 Runtime** draws the app window and is Microsoft
software under Microsoft's terms. **Visual Studio Build Tools** and a **Java JDK** are used only if you install
them yourself (for Unity / Ren'Py / Java helpers).

ModEngine's own helpers for Java, Unity, Ren'Py and Godot games are ModEngine code, covered by the ModEngine
License. ModEngine is not affiliated with Epic Games (Unreal Engine), Unity Technologies, the Ren'Py project, the
Godot Foundation or Oracle (Java).

The fonts are bundled with ModEngine; nothing is downloaded while it runs.
