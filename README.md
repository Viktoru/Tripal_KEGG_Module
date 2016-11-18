# Tripal_KEGG_Module
KEGG Module

I don't know if you are having problems installing KEGG module. 
Follow the steps here http://tripal.info/node/106 and http://tripal.info/node/132.
Next, go here http://tripal.info/node/132 and install the KEGG module or at least until you are done installing these two modules:

BLAST Module
InterProScan Module

On the documentation: You can create an analysis by going to "Add Content" link in the administrative menu and select content type
"Analysis:KEGG" to add a series of values http://tripal.info/node/132
So, I was looking into the MODULE folder>>"tripal_analysis_kegg" folder>>folder called "includes" and finally the file called 
tripal.analysis_kegg.heir_parser.inc to make the following modifications.

In line 562 of the code: You have a "looking structures" to skip the rest of the current loop. So, you comment that line of code
"//continue;" Also, you can follow the some procedure in line 591.

V--
