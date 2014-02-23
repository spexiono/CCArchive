CCArchive
=========

Computercraft programs archive for my smaller programs and utilities.


* Window  
  * Abandoned resizing box GUI.  

* Monitor time  
  * A simple program that shows the time and some other information on a 2x1 monitor.  

Tiny functions
=========
  * tcolor function  

    ```
    local function tcolor(cval) --Changes text color IF advanced computer
    	if term.isColor() then
    		term.setTextColor(colors[cval])
    	end
    end
    ```
