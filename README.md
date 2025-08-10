**AutoCensorNSFW** is a simple desktop application that automatically detects and censors exposed genitalia in images. It uses the NudeNet AI model to identify sensitive areas and applies pixelation and blurring to protect privacy.

## Features

- Supports processing individual images or entire folders of images at once  
- Detects **FEMALE_GENITALIA_EXPOSED** and **MALE_GENITALIA_EXPOSED** regions only  
- Applies a smooth pixelation + blur effect on sensitive areas  
- Saves censored images to a dedicated `censored_images` folder  
- User-friendly graphical interface built with Tkinter  
- Works on Windows without requiring Python installation (when using the provided executable)  

## Usage

- Run the executable or Python script  
- Select one or multiple images or a folder containing images  
- Process and save automatically censored copies  

## Supported Formats

- PNG, JPG, JPEG, BMP, GIF  

## Installation

You can download the pre-built executable from the [Releases](#) section or run the app from source:
