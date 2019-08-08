
#  Transforming Schema.org to ISO19139 XML

Based on recommendations from P418/ESIP science with schema.org

Use the templating scheme developed by CINERGI project for converting tabular metadata compilations to ISO, adapt to use JSON paths to locate elements in source document 

I'm using https://jsonpath.curiousconcept.com/ to test json paths. It is apparently using the JSON path php implemenation from flow communications. https://github.com/FlowCommunications/JSONPath.  This appears to be largely consitent with python implementations

more info on JSON path implementations:

java implemenation at https://github.com/json-path/JsonPath adds additional operators for expressions
    https://github.com/kennknowles/python-jsonpath-rw is python implementation that is also somewhat different
    flow communications php implementation https://github.com/FlowCommunications/JSONPath
    see https://pypi.org/search/?q=jsonpath for a bunch of python implementations...
    
    comparison of different implementations: https://cburgmer.github.io/json-path-comparison/
	
	
JSON path tester: https://jsonpath.curiousconcept.com/

