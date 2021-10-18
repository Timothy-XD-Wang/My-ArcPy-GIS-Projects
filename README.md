# MyProjects
A collection of my scripts for use with the ArcPy package intended to automate tasks in ArcGIS

1 The Buffers.py script seeks to create buffers around a featureclass in ArcGIS Pro. 
  It is meant to be a simplifications of the Multiple Rings Buffer Tool by automating the creation of subsequent buffers. 
  User inputs are fed through the ArcPy function "Buffer_analysis" to facilitate the creation of buffers. 
  This script is meant to be run using Pycharm or similar IDE. 



2 The BuffersTool.py script is a modification of Buffers.py. 
  The goal of BufferTool.py is to allow the script to be used in the creation of a custom tool directly in ArcGIS Pro
  It replaces hardcoded inputs with functions that obtains value from ArcPy parameters using the GetParameterAsText and GetParameter functions. 
  All print statements from BufferTool are also changed to the AddMessage function.

  Upon setting up a custom tool in ArcGIS Pro with the BuffersTool.py script, the following interface should appear:
  
<img width="282" alt="Screen Shot 2021-10-18 at 7 04 27 PM" src="https://user-images.githubusercontent.com/92761963/137818225-88c07b40-9426-42b4-b082-1f8af26b7998.png">
