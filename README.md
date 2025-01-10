# Boxart-Bezels
Bezels for 1:1 screens

4:3 bezels for Retroarch based on games boxart. I recommend to use pixel-art-scaling/pixel_aa.glslp shader to avoid uneven pixels in 4:3 systems (You need to use the Online updater inside Retroarch if you dont have the shader. Main menu>Online updater>Update GLSL Shaders).

# Preview

![preview](https://github.com/Vidnez/Boxart-Bezels/assets/82564218/0d291d3c-06e7-4dcc-891f-84c9fc62f99b)


# General Instructions (Applying overlays)

Open 'Quick Menu' on Retroarch (Select + X buttons) > On-Screen Overlay > Overlay Preset > Choose the .cfg file for the system in use. 

# Aligning overlays for 4:3 systems (not handhelds).

Settings ->

  - Video ->
    
    - Scaling ->
      
      * Integer Scale: OFF
      * Aspect Ratio: Custom
      * X Position: 0
      * Y Position: 50
      * Width: 720
      * Height: 540

# For GB, GBC, GBA, GG, NGP, NGPC (handhelds)

Settings ->

  - Video ->

    - Scaling ->

      - Integer Scale: ON
      - Aspect Ratio: Core provided


# For Wonderswan, Wonderswan Color and Atari Lynx

Settings ->

 - Video ->

   - Scaling ->

     - Integer Scale: OFF
     - Aspect Ratio: Core provided
    
# Saving changes

To save the changes after all the adjustments you need to go to 'Quick menu' > Overrides > Save Content Directory overrides. 

  *This step is per system.

