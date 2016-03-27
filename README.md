ua_parser C++ Library
=====================

Usage
-----

To build the (static) library:

    $ make uaparser_cpp

To build and run the tests:

    $ make test

Dependencies
------------

* boost_regex, boost_system, yaml-cpp (0.5 API)
* gtest (for testing)
* uap-core from https://github.com/ua-parser/uap-core, same directory level as uap-cpp. The newest uap-core usable with uap-cpp is 09b6d1e. See https://github.com/asuhan/uap-cpp/issues/4.

Author:
-------

  * Alex Şuhan <alex.suhan@gmail.com>

  Based on the D implementation by Shripad K and using agent data from BrowserScope.
