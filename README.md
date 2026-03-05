# Common-Unreal-Engine-Errors
I keep running into repeat errors and decided to document them since they're generally easy to solve but I keep forgetting them.

## Ghost Files. You deleted a class/file but the editor tells you it already exists
- Close the project
- Delete the Binaries and Intermediate folders
- Right-click on the .uproject file
- Click "Generate Visual Studio project files" (if using windows11 first click "Show more options")
- Open .uproject file and rebuild it

## Error  : LNK1120: 1 unresolved externals
This usually means that there's a declaration in the .h file but not definition in the .cpp file
