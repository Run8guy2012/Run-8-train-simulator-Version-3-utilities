==============================================================================
                    RUN 8 & PHOTO ENHANCER SUITE v1.0
                              USER GUIDE
==============================================================================

OVERVIEW
--------
The Run 8 & Photo Enhancer Suite is a lightweight, high-performance desktop 
application built specifically for railfans and virtual engineers. Designed 
to enhance screenshots from Run 8 Train Simulator (and general railway photography), 
this suite transforms flat raw captures into vibrant, photorealistic, atmospheric 
scenes without requiring heavy, complex image editing software.

KEY FEATURES
------------
- Pure Python & Pillow: Fast processing, light memory footprint, zero complex setup.
- Flexible Dual-Panel Interface: Dedicated left scrollbar for presets and primary 
  adjustments, with detailed atmospheric controls on the right.
- Real-Time Live Preview: Immediate visual feedback on canvas edits.
- Hold-to-Compare: Compare original vs. edited shots dynamically.
- Custom Preset Management: Save and load your own tailored color profiles as JSON files.
- Automated Batch Processing: Process entire directories of screenshots in seconds.

==============================================================================
UI LAYOUT & CONTROLS GUIDE
==============================================================================

1. LEFT PANEL: CORE CONTROLS & PRESETS
---------------------------------------
- [📁 Open Image]: Load a single raw screenshot (.png, .jpg, .bmp).
- [💾 Save Enhanced Image]: Save your edited screenshot directly to disk.

Core Image Controls:
- Sharpness: Dial in locomotive textures, ballast, and subtle trackside details.
- Contrast: Enhance depth between shadows and highlights.
- Color Vibrance: Adjust color saturation without oversaturating skin or ballast tones.
- Brightness: Fine-tune overall scene exposure.

Built-in Style Presets:
- 📂 Trackside Realistic: Balanced, subtle polish for clean everyday operation.
- ✨ Trackside Detail Pop: Crisp textures and bold contrast.
- 📸 Photorealistic DSLR: Simulates high-end DSLR camera sensor depth and tone.
- 🌅 Golden Hour / Sunset Sky: Enhances warm tones and sunset sky presence.
- 🎬 Cinematic Film Grade: Rich tones with a silver-screen aesthetic.
- 📷 Kodachrome Slide Film: Deep vintage reds, punchy contrast, classic slide look.
- 🌧️ Overcast / Gloomy Day: Cool tones and muted vibrance for stormy setups.
- 🌆 Twilight Blue Hour: Deep blues and dusk lighting ideal for yard scenes.
- 🖤 Classic Black & White: High-contrast monochrome conversion.
- 🔄 Reset Controls: Instantly reset sliders back to default state.


2. RIGHT PANEL: ATMOSPHERE, WEATHER & EXPORT
--------------------------------------------
Color Channel Tuning:
- Red / Green / Blue Channel Tone: Independent control for custom color cast adjustments.

Atmosphere & Weather Effects:
- Sky Atmosphere Boost: Brightens and enriches sky regions without blowing out ground detail.
- Sunset Glow Intensity: Injects warm ambient evening light into the horizon.
- Fog / Mist Thickness: Adds realistic valley fog or morning mist over lower terrain.
- Fall Foliage Intensity: Converts green foliage into vibrant autumn colors.
- Headlight Beam & Glow: Creates realistic beam flares and volumetric headlight bloom around bright light sources.
- Headlight Beam Spread: Adjusts the wide-angle spread of the headlight beam polygon.
- Rainbow Intensity: Adds a soft, natural 7-color rainbow arc to sky scenes.
- Rainbow Vertical Offset: Elevates or lowers the rainbow height across the frame.

Tools & Utilities:
- 💾 Save Custom Preset: Export your exact slider settings to a reusable JSON file.
- 📂 Load Custom Preset: Import any previously saved JSON preset file.
- 📁 Batch Process Folder: Apply current slider settings across a whole folder of screenshots.
- 👁️ Hold to Compare (Original): Press and hold this button to temporarily reveal your raw image.


==============================================================================
QUICK START GUIDE
==============================================================================

SINGLE PHOTO ENHANCEMENT:
1. Click [📁 Open Image] on the top left.
2. Select a preset (e.g., "Photorealistic DSLR" or "Golden Hour").
3. Fine-tune atmospheric sliders like "Fog / Mist" or "Rainbow Intensity" on the right.
4. Hold down [👁️ Hold to Compare] to check your improvements against the original.
5. Click [💾 Save Enhanced Image] at the top of the left sidebar to save your photo.

BATCH PROCESSING MULTIPLE SCREENSHOTS:
1. Load a sample image and set up your preferred adjustments/presets.
2. Click [📁 Batch Process Folder] on the bottom right panel.
3. Select the folder containing your raw screenshots when prompted.
4. Select (or create) an output destination folder.
5. The suite will process and save all images automatically!

==============================================================================
SYSTEM REQUIREMENTS & DEPENDENCIES
==============================================================================
- Python 3.8 or newer
- Pillow library (pip install Pillow)
- Tkinter (standard with Python installation)

==============================================================================
CREDITS & COMMUNITY RELEASE
==============================================================================
Developed for the Run 8 Train Simulator community. Enjoy capturing the rails!