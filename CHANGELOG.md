
0.1.1 / 2015-01-23
==================

  * Add internal helper #remove_links? for association payloads
  * Do not send `links: {}` if new object, and empty associations

0.1.0 / 2014-12-03
==================

  * `middleware` and `ssl` attributes are inheritable
  * Support custom faraday connection middleware with `#middleware` block
  * update README with usage

0.1.0.pre.3 / 2014-11-11
==================

  * Has One relationships use plural names in side-loading lookups.

0.1.0.pre.2 / 2014-11-11
==================

  * Set Accept header properly to 'application/json'
  * Add spec for Resource.all with params

0.1.0.pre.1 / 2014-10-19
==================

  * Add yarddoc to associations_concern
  * Add error handling and parsing of Bad Requests
  * Parse `has_one` and `has_many` links attribute from JSONAPI
  * CRUD is supported
  * Support create, find, all finders
  * Create query support
  * Basic serialization and association building.

