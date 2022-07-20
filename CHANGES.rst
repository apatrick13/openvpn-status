0.2.2 (2022-07-20)
------------------
Fix exception while parsing timestamp -> add new timestamp format support

0.2.1 (2019-08-27)
------------------

- Fix GH-11: Fix the parser which throws ``ValueError`` on interrupted stream.

0.2.0 (2017-10-20)
------------------

- Feature GH-1: Add support to TAP mode of OpenVPN servers by parsing virtual
  addresses as MAC and IP both.
- Feature GH-4: Add support to client-config-dir (ccd) and iroute.
- Fix GH-2: **BREAK-COMPATIBILITY** Use real or virtual addresses as the key
  of client_list and routing_table, instead of using common name.

0.1.1 (2016-06-29)
------------------

- Fix GH-3: The depended six must later than 1.9.0 because we need the
  "python_2_unicode_compatible" decorator.

0.1.0 (2015-06-19)
------------------

The first release.
