Result
======

Definition
----------
The **IATI activity standard** enables the publishing of information on measurable results from an ``iati-activity``, through use of the ``result`` element.

| Via:

* ``result`` - a measurable result of aid work.
 
Considerations
--------------
When using the **IATI activity standard** to declare *result*, the following should be considered:

* Any ``iati-activity can have either one or multiple ``result``.

* A ``result`` should have a ``title`` and a ``description`` to clarify the information being detailed.

* Every ``result`` should include an ``indicator``, which in turn details a period of time, and then a ``target`` and ``actual`` measure.

* An ``indicator`` can have a ``title`` and a ``description`` to clarify the information being detailed.

* An ``indicator`` can be repeated within any ``result`` dataset.

* It is also recommended to include a ``baseline`` measure for each ``result`` recorded.

* Any ``target``, ``actual`` and ``baseline`` can have attached a ``comment`` to provide additional narrative or information.

* The free-text instances of ``title``, ``description`` and ``comment`` can be repeated for multiple languages, using ``xml:lang``.

* The free-text instances of ``title``, ``description`` and ``comment`` should avoid use of text in CAPITALS, where possible. 
 
Further guidance
----------------

Reference pages:

* :doc:`related-activity </activity-standard/iati-activities/iati-activity/result/>`