Change Log
==========

Version 0.4.3
-------------

 * Another workaround for bash -echo problems
   [#44](https://github.com/passy/build-time-tracker-plugin/issues/44)

Version 0.4.2
-------------

 * Resurface build success status in SummaryReporter
   [#40](https://github.com/passy/build-time-tracker-plugin/issues/40)

Version 0.4.1
-------------

 * Downgrade to JLine 2.11 to avoid terminal problems.
   [#41](https://github.com/passy/build-time-tracker-plugin/pull/41)

Version 0.4.0
-------------

 * Upgrade to Gradle 2.1. ABI-compatible with pre Gradle 2.0.
   [#38](https://github.com/passy/build-time-tracker-plugin/pull/38)
 * Add `barstyle` option to SummaryReporter
   [#39](https://github.com/passy/build-time-tracker-plugin/pull/39)

Version 0.3.0
-------------

 * Possibly breaking change: CSV now also logs information about CPU, memory and
   operating system

Version 0.2.0
-------------

 * New: Summary reporter gives you daily and all-time stats
