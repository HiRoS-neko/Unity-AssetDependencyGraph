# Unity - Asset Dependency Graph 

New License and Contribution Guidelines: 28/10/2020

This project provides a basic Asset Dependency Graph for Unity using the new [GraphView](https://docs.unity3d.com/2019.2/Documentation/ScriptReference/Experimental.GraphView.GraphView.html) API.

![](Images~/Example.png?raw=true)

## Install instructions
1. Close Unity and open the `Packages/manifest.json` file
2. Add `"com.harryrose.assetdependencygraph": "https://github.com/hiros-neko/Unity-AssetDependencyGraph.git",` to the `dependencies` section

## Usage

The Asset Dependency Graph Window can be opened via the `Window > Analysis >Asset Dependency Graph` file menu

![](Images~/Usage.png?raw=true)

Once the window is open:
1. Select the root asset you want to inspect in the Project window
2. Click the `Explore Asset` button in the graph window

## Tested against
2021.3.11f1
