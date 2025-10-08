
```
⚙️ 4-Stroke Engine Model (Autodesk Inventor)

A detailed 3D parametric model of a single-cylinder, four-stroke internal combustion engine, fully modeled and assembled using Autodesk Inventor Professional.

## 🚀 Project Overview

This repository contains all the necessary Part (.ipt) and Assembly (.iam) files to visualize and simulate the fundamental mechanical motion of a 4-stroke engine (Intake, Compression, Power, and Exhaust).

### Key Features:

* Realistic Motion: The assembly is fully constrained, allowing the crankshaft, connecting rod, and piston to move realistically.

* Parametric Design: Key dimensions are driven by parameters, allowing for easy modification (e.g., changing the bore or stroke).

* Detailed Components: Includes the core mechanical elements: Crankshaft, Piston, Connecting Rod, Cylinder Block, and Valves/Camshaft.

## 🛠️ Requirements

To open and interact with the model files:

* Software: Autodesk Inventor Professional (Recommended: 2020 or later).

* Operating System: Windows, macOS (with Inventor/Fusion 360 compatibility).

## 📂 Repository Contents

The main files for the engine model are located in the primary folder:

| File Type | Extension | Description | 
| ----- | ----- | ----- | 
| Main Assembly | .iam | The primary file that links all parts and contains all motion constraints. | 
| Part Files | .ipt | Individual 3D models of components (Piston, Crankshaft, etc.). | 
| Drawings (Optional) | .idw / .dwg | Technical drawings, dimensions, and Bill of Materials (BOM). | 

## ▶️ Viewing and Simulating Motion

1. Clone or Download the repository files.

2. Open the main assembly file (4_Stroke_Engine_Assembly.iam) in Autodesk Inventor.

3. In the Model Browser, locate the rotational constraint applied to the crankshaft (often named "Crank_Rotation" or similar).

4. Right-click on the constraint and select Drive Constraint. Use the controls to cycle the engine through its four strokes and observe the linkages.

## 💡 Usage and Modification

Feel free to use this model for personal projects, academic study, or as a base for further development.

* Study: Analyze the geometry and motion of the crank-slider mechanism.

* Modify: Edit the .ipt files to change dimensions and experiment with different engine configurations.

* Simulation: Export geometry to other software for FEA (Finite Element Analysis) or CFD (Computational Dynamics) studies.
```