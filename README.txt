-- Python decision tables --

To use XLS format, the xlrd module is required to be available/installed. 
You can get this from:http://www.lexicon.net/sjmachin/xlrd.htm 
To install, you will unzip the xlrd package, and then run pythong
setup.py install. 

To use: look in the pydt_test.py for an example on how to use it. Of
most interest will be the Example.xls usage - it is both an example
and a test case. The loading of the decision table data from the XLS
into memory is a separate step so the cost of parsing the XLS file
(which may be large) is small (also it means you could use your own
tabular data source other than XLS if you wanted to).


Enjoy !

Michael Neale
http://www.michaelneale.net
http://github.com/michaelneale
http://twitter.com/michaelneale
