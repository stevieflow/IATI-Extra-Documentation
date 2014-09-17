Example Usage
~~~~~~~~~~~~~
The ``narrative`` child element can be used to declare freetext for the ``title`` parent element.

.. literalinclude:: ../../../../activity-standard-example-annotated.xml
	:language: xml
	:start-after: <!--result starts-->
	:end-before: <!--result ends-->
	:emphasize-lines: 3	

The ``narrative`` element can be repeated for any language additional to the default language set in ``iati-activity``, by using the ``xml:lang`` attribute:
		
.. literalinclude:: ../../../../activity-standard-example-annotated.xml
	:language: xml
	:start-after: <!--result starts-->
	:end-before: <!--result ends-->
	:emphasize-lines: 4
	
Changelog
~~~~~~~~~

2.01
^^^^

| The ``narrative`` element was introduced in 2.01.