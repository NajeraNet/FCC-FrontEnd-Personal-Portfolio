# FCC-FrontEnd-Personal-Portfolio

# Application

## Notes:

* Set font size for easy rem calculations.
* default document font size = 16px, 1rem = 16px, 100% = 16px (100% / 16px) * 10 = 62.5%, 1rem = 10px, 62.5% = 10px
 
* A few media query to set some font sizes at different screen sizes.  
* This helps automate a bit of responsiveness.  
* The trick is to use the rem unit for size values, margin and padding. 
* Because rem is relative to the document font size when we scale up or down the font size on the document  
* it will affect all properties using rem units for the values. 
* I am using the em unit for breakpoints The calculation is the following 
 screen size divided by browser base font size 
* As an example: a breakpoint at 980px  980px / 16px = 61.25em 

