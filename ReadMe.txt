Viga Studios Plugin
09/07/2020

This plugin is designed for sorted folders, i.e. a folder having static fbx meshes should not be mixed with wav, tga or skeletal fbx meshes.

Steps to install Plugin in project - 
1. Copy Plugin folder inside "Plugin" of your project
2. Open Project
3. Enable "Editor Scripting Utilities" and "Python Editor Script Plugin" in Plugins
4. Go to Project Settings -> Python -> 
	a. Enable Develper Mode
	b. In "Additional Paths", after going inside your project folder, browse to 
		Plugins -> Viga7Plugin0907 -> Select Folder "StartupScript"
   and restart the editor.
5. In the Content Browser, go to Viga7Plugin0907Content,
   Right click "Viga7EditorUtilityWidget" -> Run Editor Utility Widget
6. Enter the address of the folder of the files in the given space as shown and choose the file format.
	e.g. 'D:/UE4 Folders/VIGAfiles/Assets/static_fbx/'

