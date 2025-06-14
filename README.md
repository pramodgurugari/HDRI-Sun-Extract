# HDRI-Sun-Extract

![stops](https://github.com/user-attachments/assets/109935f6-5614-4481-be67-b84baac3ca31)

![Capture](https://github.com/user-attachments/assets/c3c946d5-19d6-41b7-a6dd-906c4b3d1bda)


HDRI Sun Light Extract (Tool)
Download Link :-https://pramodify.gumroad.com/l/beseh
https://www.nukepedia.com/gizmos/image/hdrisunextract
If you truly want to achieve a realistic match with onset lighting in a 3D environment, it is crucial to extract the key light sources, such as the sun or other significant light emitters, from the HDRI and accurately position them within the 3D space using lights.
The importance of extracting sunlight:-
In particular, cannot be overstated. While it is common practice to paint out the sun and bloom areas from the HDRI and export the image for use as a diffuse and reflection map—which is indeed beneficial—this approach alone may not suffice for photorealistic rendering. The sunlight and other key light sources in an HDRI typically possess a wide dynamic range in terms of exposure and color information. By extracting and replicating these lights separately within the 3D scene, you can effectively recreate their intensity, direction, and color attributes, resulting in a far more realistic and accurate representation of the original lighting conditions. This process ensures that the lighting in your render has the depth, variation, and accuracy needed to achieve a truly photorealistic output.
The Gizmo provides assistance in analyzing and extracting detailed information about sunlight from a Latitude-Longitude HDR image. This extracted data can then be utilized to accurately recreate the lighting conditions of the scene by applying the information to a Dome Light within your preferred 3D lighting software or rendering package.
When you first launch the HDRI Sun Light Extract Gizmo, you are presented with several key options:
1. Enable Edits: This must be switched ON to start editing. If you wish to view your original HDRI without any edits, simply turn it OFF.
2. Sun Location: The first step is to move the point towards the sun's center position. This is important for accurately analyzing the HDRI for various attributes.
3. HDRI Data Analysis: This tool analyzes the maximum and minimum pixel values of the HDRI, allowing you to understand how much information your HDRI contains. Note: It is always good practice to analyze the data both before starting and after applying the Sun Extract settings to ensure there is no significant loss of data. The values before and after should ideally remain close.
4. Sun Extractor: Using the minimum and maximum range values, you can extract the sun from the HDRI. In most cases, the default values (80%) for min and max will work well. If further adjustments are needed, there are options to tweak these values. Additionally, if you wish to clamp your HDRI to a specific maximum value, you can enable the Clamp HDRI option.
5. Neutralize Sun Color: When enabled, this option neutralizes the color of the HDRI sun, allowing you to assign your own sun color in Nuke or through your light rig.
6. Sun Temperature: This allows you to pick the temperature color of your HDRI sun and transfer it to your dome light color.
7. Auto Roto: If enabled, a roto will be automatically generated based on the sun's location point. You can adjust the edge softness as needed. If you disable this option, you have the flexibility to perform manual roto adjustments for the sun, if required.
By following these steps, you can effectively analyze, adjust, and extract sunlight from your HDRI for use in your lighting workflow.



https://github.com/user-attachments/assets/0f3e1b53-ed83-42f9-a33d-c0a47770a966

