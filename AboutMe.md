# HouPy
Explaining whole HouPy functions. 
#Importimg Houdini module

import hou

#Make folders in node

def folder(folderName):
	for sel in hou.selecedNodes():
		sel.addControlParmFolder(folderName)
