# Pip Qt Unreal plugin

This Unreal plugin is a simple wrapper around pip-qt.  
It adds the command `import pip_qt;pip_qt.show()` to the Unreal menu.  
It still requires the user to install the pip-qt dependency themself.  

## manual instructions
1. pip install the dependencies from the requirements file
2. place the plugin in your unreal plugin folder
3. enable the plugin and restart unreal.
4. plugin button should now show in the toolbar

dependencies
- [pip-qt](https://github.com/hannesdelbeke/pip-qt)
- [unreal-qt](https://github.com/hannesdelbeke/unreal-qt)
