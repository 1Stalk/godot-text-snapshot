# Godot Script Exporter Plugin
This repository contains the source code for "Script Exporter" plugin for Godot Engine.

This tool allows you to select multiple GDScript files from your project and export their contents into a single text file or copy them directly to your clipboard. It's very useful for sharing code or preparing it for AI assistants.

## Screenshots

**Main Window:** Select scripts, choose options, and export.
![Script Exporter Window](visuals/1.png)

**Example Output:** Exported text is cleanly formatted with headers for each script.
![Example of exported text file](visuals/2.png)

**How to Access:** Plugin is easily accessible from `Tools` menu.
![Accessing the plugin via the Tools menu](visuals/3.png)


## Installation

1.  **(Recommended)** Find and install "Script Exporter" in Godot Engine's Asset Library tab.
2.  **(Manual)** Download this repository, and copy `addons/ScriptExporter` folder into `addons` folder of your Godot project.

Then, enable the plugin in `Project -> Project Settings -> Plugins`.

## About this Repository

Actual plugin code is located in `addons/ScriptExporter` directory. This structure is required for the Godot Asset Library. `README.md` file in that directory contains the user-facing documentation displayed in the Asset Library.

## Acknowledgements

This plugin was inspired by the idea and great UI of [Scene Tree as Text](https://github.com/CyrylSz/scene-tree-as-text) plugin by Cyryl Szczakowski.

Both plugins complement each other perfectly. While **Scene Tree as Text** exports the *structure* of your scenes, **Script Exporter** provides the *code* that brings those scenes to life. Using them together is a great way to get a complete snapshot of your project for sharing or analysis.

## License
This project is licensed under the MIT License.