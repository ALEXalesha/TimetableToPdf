# Changelog

What changed for the user in each release. The full text of each release, in English and
Russian, is on the [releases page](https://github.com/ALEXalesha/TimetableToPdf/releases).

## 2.1.0 - 2026-09-24 - The window opens where and how large it was closed, maximized too

The geometry is saved with the other settings when the window closes and restored at the next start. A damaged value, or a window whose title bar would not be on any screen, gives the default size. The settings file is now written through a temporary one.

## 2.0.0 - 2026-09-22

First public release on GitHub. Version 2.0 is the Qt rewrite of the window.

**The window is Qt (PySide6) now, not tkinter.** Resizing no longer lags, the Windows dark theme is picked up automatically, and a file can be dropped straight into the window.
