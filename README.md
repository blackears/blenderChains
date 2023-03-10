# Blender Chains

This is an asset library with a geometry nodes setup to let you quickly create and manipulate chains.

![Fur shader demo](doc/chain_image.png)

## Installation

Download the chains.blend file and place it on your hard drive.

Open User Preferences
* Open the File Paths tab.  
* In the Asset Libraries section, click on the + symbol which will open a file browser.  
* Browse to and select the directory that contains the chains.blend file you downloaded.
* Click Accept
* Give the asset entry the name "Chains", or whatever other name you find memorable.

## Usage

![Fur shader demo](doc/chains-manipulateChain.gif)

Once you have registered the chains.blend file with the asset manager, you will be able to open Blender's Asset Browser in any window.  This project's assets will be listed under the name you chose in the installation step.

Create a new curve object if you have not done so already.  This will be used for the spine of your chain.

Select your curve and open the Geometry Nodes tab.  Click on the New+ button at the top of the geometry nodes area.

Open the Asset Browser.  Open the Chains category - the "chainBuilder" node should be listed there.  Click and drag it into the geometry nodes area.  Click the dropdown at the top of the geometry nodes area.  Pick "chainBuilder" from the menu.  

Open the Modifiers panel and take a look at the options listed in the geomerty node section.  Set the Link Object to the mesh you want to use for drawing the individual chain links.  Change the other parameters to your liking.

## Support

If you find these assets useful, please consider buying me a coffee on Kofi:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Y8Y43J6OB)