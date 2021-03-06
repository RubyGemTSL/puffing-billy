v0.9.1, 2016-07-28
------------------
  * Rescue LoadErrors during driver registration [#170](https://github.com/oesmith/puffing-billy/pull/170)

v0.9.0, 2016-07-23
------------------
  * Add Watir web driver support [#158](https://github.com/oesmith/puffing-billy/pull/158)
  * Fix response headers by anticipating EventMachine::HttpResponse behavior [#162](https://github.com/oesmith/puffing-billy/pull/162)
  * Support using a Regexp in path_blacklist [#163](https://github.com/oesmith/puffing-billy/pull/163)

v0.8.0, 2016-06-02
------------------
  * Add optional after_cache_handles_request callback for manipulating cached responses [#149](https://github.com/oesmith/puffing-billy/pull/149)
  * Remove rspec-expectations deprecation warning for README example [#153](https://github.com/oesmith/puffing-billy/pull/153)
  * Make stub requests accessible [#154](https://github.com/oesmith/puffing-billy/pull/154)

v0.7.0, 2016-05-05
------------------
  * Change WebKit driver to ignore SSL errors [#140](https://github.com/oesmith/puffing-billy/pull/140)
  * Add documentation and specs for stubbing out options requests [#141](https://github.com/oesmith/puffing-billy/pull/141)
  * Support distinguishing non-POST requests in cache based on request body [#148](https://github.com/oesmith/puffing-billy/pull/148)
  * Allow Puffing Billy to run with custom host [#150](https://github.com/oesmith/puffing-billy/pull/150)

v0.6.2, 2015-11-23
------------------

  * Enhanced error output for proxy handling [#125](https://github.com/oesmith/puffing-billy/pull/125)
  * Use options to create webkit driver [#129](https://github.com/oesmith/puffing-billy/pull/129)
  * Billy config and Capybara::Webkit config compatibility [#130](https://github.com/oesmith/puffing-billy/pull/130)
  * Output the request method when proxy returns an error [#134](https://github.com/oesmith/puffing-billy/pull/134)

v0.6.1, 2015-08-25
------------------

  * Fix `instance variable not initialized` warnings [#107](https://github.com/oesmith/puffing-billy/pull/107)
  * Add regex support to whitelist [#111](https://github.com/oesmith/puffing-billy/pull/111)
  * Support basic auth in requests [#121](https://github.com/oesmith/puffing-billy/pull/121)
  * Added alternative to run VCR in parallel [#122](https://github.com/oesmith/puffing-billy/pull/122)

v0.6.0, 2015-08-25
------------------

  * Fix uninitialized constant error in Minitest (#109)
  * Add support for customizing Billy proxy host (#112)
  * Add support for internal proxies (#118)

v0.5.1, 2015-04-22
------------------

  * Selenium Chrome Billy Driver (#98)

v0.5.0, 2015-02-22
------------------

  * Rubocop code cleanup (#89)
  * Create option for strip query params in request stub (#93)
  * Require compatible version of em-http-request (#94)

v0.4.1, 2015-01-02
------------------

  * Use Addressable for all URI parsing

v0.4.0, 2015-01-02
------------------

  * Add new configuration to merge cache hits by URL regex (#76)
  * Allow pipes in URLs by switching to Addressable (#84)
  * Consistently ignore SSL errors (added to selenium driver) (#85)

v0.3.0, 2014-12-29
------------------

  * Fixing a bug where proxy to SSL can duplicate https in the request_url (#36)
  * Refactor proxy responses (#37)
  * Update http_parser to 0.6.0 and remove CONNECT request hack (#38)
  * Allow configurable Billy proxy port (#40)
  * Refactor handlers (#41)
  * Mark step definitions as ruby code (#52)
  * Adds EventMachine timeout configuration (#57)
  * Support dynamic jsonp with params (#58)
  * Writing error messages to the logger rather than stdout (#69)
  * Do not recommend changing javascript_driver config (#70)
  * README link pointing at wrong target (#73)
  * Adding example config to README for playing nicely with Webmock, VCR (#74)
  * Make dynamic_jsonp regex less brittle (#81)

v0.2.3, 2014-02-07
------------------

  * Fixed facebook spec (#24)
  * Check for existing persistent cache files on demand (#26)
  * Lazy-loading proxy and other minor fixes (#28)
  * Support service-oriented architectures, scope cache to scenarios, and sort JSON in POSTs to avoid duplicate cache files (#30)
  * Set the minimum version of capybara-webkit to 1.0.0 (#31)
  * Updated gems, cache request headers, handle non-successful responses, ability to stop new connections (#33)
  * Add requires matching gem name (#34)
  * Remove duplicated rspec devel dependency (#35)

v0.2.1, 2013-05-12
------------------

  * Add cucumber documentation to readme. (#12)
  * Use multi_json (#13)
  * Remove require from Gemfile example (#14)
  * Add a README example of returning headers (#16)

v0.2.0, 2013-03-17
------------------

  * Update README with HTTPS quirk and trailing slash behaviour. (#3)
  * Fixes to work with Capybara-Webkit (#6)
  * VCR-like cache (#7)

v0.1.3, 2012-11-05
------------------

  * Implemented caching

v0.1.2, 2012-10-12
------------------

  * Slightly saner driver setup
  * Updated README

v0.1.1, 2012-10-12
------------------

  * Content encoding fixes
  * Updated README

v0.1.0, 2012-10-11
------------------

  * Initial release
