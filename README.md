https://artylope.github.io/test-lottie/

# Personal Guide to having animated lottie animations

## To Export assets from Figma to AE
To enable export of assets from Figma to After Effects,
1. Install the AEUX Plugin in Figma [AEUX Plugin Download Link](https://aeux.io/)

2. Install the AEUX Plugin in After Effects [AEUX Plugin Download Link](https://aeux.io/)
then you can use the AEUX Plugin on Figma to "Send the selection to Ae" with After Effects running. 


## To Export animations from AE into a lottie JSON File
To allow the exporting of animation from After Effects into a JSON file that you can use in your project. 

 1. Install the BodyMovin Plugin in After Effects -  [Bodymovin Plugin
    Download Link](https://aescripts.com/bodymovin/)
    
 2. Select the comp you want to render and rename and select where you want to store the exported JSON file.
 3. Click "Render" 
 
 
## To render lottie JSON file on a webpage

 1. Read here [Guide for rendering Lottie on the web](http://airbnb.io/lottie/#/web)

# Some tips

##  If using expressions (e.g. Mister Horse Anmiation Presets) and want to convert expressions to key frames
You can convert the expression to keyframes, by selecting the transform property you assigned the expression to (e.g. Position) then clic to the menu Animation > Keyframe Assistant> Convert Expression to keyframe. https://github.com/airbnb/lottie-web/issues/2265. Delete the original expression after converting to keyframes.

## If "render fail" when rendering in Bodymovin
If you have downloaded the extension from Adobe exchange uninstall it and re-install after downloading from aescripts.com. You will also need to download zxp installer. Install the .zxp file of bodymovin and then go into AE edit>preferences>general>scripting and expressions and then allow scripts to write files and access network. Bodymovin should work then. https://github.com/airbnb/lottie-web/issues/2265 
