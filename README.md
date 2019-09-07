# DT Compile Time Tracker
Unity editor extension which tracks compile time.

How do you optimize compile time? [Read This!](https://medium.com/@darrentsung/the-clocks-ticking-how-to-optimize-compile-time-in-unity-45d1f200572b#.q8h3v6a4f)

### Add as submodule on your Unity project repository:
``git submodule add https://github.com/k10czar/DTCompileTimeTracker.git "Assets/Plugins/CompileTimeTracker"``

### Features:
Compile time is logged automatically to console and recent compile times can be viewed in the tracker window (Window -> Compile Time Tracker Window)

It also attempts to detect errors by comparing the number of error logs before compiling + after compiling, but it's not completely accurate as some code will cause errors logs during [InitializeOnLoad] or OnValidate calls.

![Window Screenshot](WindowScreenshot.png)

![Menu Screenshot](MenuScreenshot.png)
