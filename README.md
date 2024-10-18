# Image to Geometry Dash Editor Guide

This guide will walk you through the steps to convert an image into Geometry Dash levels using the SPWN language and Geometrize.

## Prerequisites

Before you start, make sure to install the following:

1. [SPWN Language](https://github.com/Spu7Nix/SPWN-language/tree/v0.6-beta)
2. [Geometrize](https://www.geometrize.co.uk)

## Instructions

1. **Install SPWN Language**: Follow the instructions provided in the SPWN Language GitHub repository.

2. **Install Geometrize**: Download and set up Geometrize from its official website.

3. **Input Your Image**: Open Geometrize and input the image you want to convert.

4. **Select Circles**: Choose the circle shape for the geometrization process.

5. **Generate the Image**: Continue generating the image until you are satisfied with the result.

6. **Export the File**:
   - Press the export button.
   - Choose `.json` format for the export.

7. **Upload to GitHub**:
   - Open the GitHub site connected to this project.
   - Input your file into the repository.
   - Wait for the system to process and output a new file.

8. **Build with SPWN**:
   - Open the command prompt.
   - Type the following command:
     ```bash
     spwn build (path to the new outputted file)
     ```
   **Warning**: This will overwrite the newest level in Geometry Dash.
