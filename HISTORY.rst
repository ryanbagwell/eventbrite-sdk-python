.. :changelog:

History
-------

3.1.0 (2014-05-11)
------------------

* Added control over expansion of response. Documentation at http://www.eventbrite.com/developer/v3/reference/expansions/

3.0.5 (2014-04-24)
------------------

* Removed 'content-type' header from all GET requests. Thank you @xxv for identifying the problem and contributing code.

3.0.4 (2014-03-12)
------------------

* Resolved the search result response problem where filtering did not work.


3.0.3 (2014-03-02)
------------------

* Fixed import issue with ``__version__``. Thank you @meshy  and @longjos for identifying the problem.

3.0.2 (2014-01-30)
------------------

* Event creation now working.
* Added feature allowing the use of Eventbrite API url at test servers. Should expedite development of tricky post actions.


3.0.1 (2014-01-30)
------------------

* Added reverse mapping for ``get_event_ticket_class()`` method.
* Added ``events`` mapping to provide GET access to the Event endpoint.
* Removed several deprecated JSON mappings.

3.0.0 (2014-01-28)
------------------

* Initial release of 3.0.0 client

3.0.0-alpha (2014-12-05)
------------------------


* Inception
