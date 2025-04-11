# Cellprofiler

Dear CellProfiler team,

I'm currently using CellProfiler 4.2.8 on Windows on classifying nuclei based on how much they overlap with different marker masks the in liver tissue sections. 

My need and situation:
I want to classify the cell types by the nuclei in which masked markers, the point is sometimes the nuclei is in the mask CK18 and mask CK7 or just touched which the nuclei then be defined as CK18 cell, CK7 cell, and other cell. I also want them to validated in overlay.
**(the total nuclei number is always more than the sum of CK18 + CK7 + other cell).** 

My aim here is to define the nuclei overlap or colocalize over 30% in the mask area of CK18 or CK7 or background. 
For example, CK18 cell: >31% The overlap of Nuclei in CK18 mask. 

Note: The CK18 and CK7 are express in cytoplasm so I set the threshold to capture the area as primary objects

Here is my cppipe and I can't find a way to set the overlap rate by classify or filter objects. :(




Thank you very much in advance!

Best regards,
