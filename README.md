lein-test-out is a leiningen plugin that runs all your tests and outputs to a file in junit XML or TAP format.

Installation
============

Add lein2-test-out as a plugin in your project.clj. E.g.:

      :plugins [[lein2-test-out "0.2.1"]]


Usage
=====
    lein test-out
test-out optionally takes an output format, and a filename to write to:
    lein test-out junit test-results.xml
Valid output formats are "junit" and "tap". 


History
=======

0.2.1
-----

 * Fix dependency declaration
 * Upgrade clojure/tools.namespace

0.2.0
-----

 * Leiningen 2 release - renamed plugin to lein2-test-out

0.1.0
-----

 * Leiningen 1 release by arohner
 

License
=======
EPL, the same as Clojure
