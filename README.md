[![Apache Sling](https://sling.apache.org/res/logos/sling.png)](https://sling.apache.org)

&#32;[![Build Status](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-commons-cache-impl/job/master/badge/icon)](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-commons-cache-impl/job/master/)&#32;[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-commons-cache-impl&metric=coverage)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-cache-impl)&#32;[![Sonarcloud Status](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-commons-cache-impl&metric=alert_status)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-cache-impl)&#32;[![Contrib](https://sling.apache.org/badges/status-contrib.svg)](https://github.com/apache/sling-aggregator/blob/master/docs/status/contrib.md) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

# Apache Sling Cache API Implementation support library

This module is part of the [Apache Sling](https://sling.apache.org) project.

This is support jar for implementing Cache services. It contains an abstract implementation of all the in
memory versions of cache that the cache service has to supply leaving instance, cluster invalidated and cluster
replicated caches upto the supporting cache library.


Acknowledgments

This code was based on a module from Sparse Content Map 29 September 2012 (git:sha1:a222df1937434ad3f07bf6c4f60b19524a158bcb), which itself was based on a snapshot of a 
module in Sakai Nakamura 27 Jan 2011 (git:sha1:b9d8e65b733ec7c35a3d194c9a5dc12acf13cb34). All know contributors to code in this module have been
contacted for permission to grant license to the Apache Foundation.
