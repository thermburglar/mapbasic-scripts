"#mapbasic-scripts" 
Various scripts written in MapBasic to automate data manipulation and cartography tasks in 
the MapInfo environment. Written by Erin Comparri 2006-2007. 

'*
' Hotspot Calculator 
' A few tools that help with the preparation of hotspot maps
' "Hotspot" maps create a raster choropleth layer over the basemap, showing the intersection of predefined (desirable) ranges of socio-economic indicators.
' Automates tasks related to scaling and calculating the raster grid scores that would otherwise have to be performed in a more robust data analysis progam.

'*
'LabelZoom
'This is a tool to change the mapper to the correct zoom for labeling
'then change it back again, naturally
' Copyright (right!) 2005 Chad Christensen
' 12 May 2005
'Modified 27 July 2006 by Erin Comparri
'Now reverts back to last editable layer after drawing boundary box and then makes
'cosmetic layer unselectable.

'*
'  Layout_Clone
'  Clones layout windows to easily maintain consistent styling throughout a map series.
'  Copyright 2007 Erin Comparri

'*
' Title: MarketPlanMap_v2007.MBX
' Final and Scenario Selection Tool for Physical Store Real Estate Analysis
' Date: May 15, 2007
' Copyright: Erin Comparri 2007

'*
' MITools_v4
' Revised on September 6, 2006 
' The Following parts Copyright 2006 Erin Comparri:
' Subs WindowFinder, OpenWindows, WinMinimizer
' WindowFinder was completly rewritten to utilize MultiListBoxes and to make
' bigger list windows.  OpenWindows is called from WindowFinder to implement the
' multilist box capabilities.  WinMinimizer minimizes all windows in the workspace.
' Revised on April 3, 2007
' Removed unecessary parts, rerouted paths, etc.
' ScaleIt code replaced with modified ScaleIt2 code from ScalebarKM.mb 

'*
'Object Recenter
'This tool recenters polygons based on a user defined point

'*
' Street_sort
' Resorts street layers so highway labels are on the bottom and real street names are on top.
' Copyright (right!) 2006 Erin Comparri
' 20 November 2006

'*
' StyleCloner 
' Tool that copies override styles from one map layer to another. Aids stylistic continuity across map frames.
' Copyright (right!) 2006 Erin Comparri
' 11 September 2006

'*
' TradeArea_Rollup
' Creates trade area polygons for each store from zipcode boundaries

'*
'Window Re-Center
'This is a tool that recenters the current map window on a selected point
' Copyright (right!) 2006 Erin Comparri
' 27 July 2006

'*  Program: WSpace.mb
'*  Purpose:
'*  Changes made March 20, 2007 (Erin Comparri)
'*  Changed "In/Out" Value to "Non-Sacred Store"
'*  Added category for "Approved Store" in Final Plan Map
'*  Altered symbols for market points to increase readability in b/w 
'*  Changed 29 March 2007 to utilize premade basemaps so cosmetic changes can be made more easily.

