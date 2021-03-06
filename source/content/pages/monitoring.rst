Monitoring
==========

:category: page
:slug: monitoring
:sort-order: 11

Capturing and analyzing data about your production environment is critical
to proactively deal with stability, performance, and errors in a web 
application.

There are several important resources to monitor on the operating system 
and network level of a web stack.

1. CPU utilization
2. Memory utilization
3. Persistence storage consumed versus free
4. Network bandwidth and latency

Application level monitoring encompasses several aspects. The amount of time
and resources dedicated to each aspect will vary based on whether an 
application is read-heavy, write-heavy, or subject to rapid swings in traffic.

1. Application warnings and errors (500-level HTTP errors)
2. Application code performance
3. Template rendering time
4. Browser rendering time for the application
5. Database querying performance


Monitoring Third Party Services
-------------------------------
`New Relic <http://newrelic.com/>`_. Application and database monitoring as
well as plug ins for capturing and analyzing additional data about tools in
your stack.

`CopperEgg <http://copperegg.com/>`_ is lower-level monitoring on server and 
infrastructure. It's popular with DevOps shops that are making changes to
their production environments and want immediate feedback on the results
of those modifications.

`Status.io <http://status.io/>`_ focuses on uptime and response metrics 
transparency for your users.

`PagerDuty <http://www.pagerduty.com/>`_ alerts a designated person or group
if there are stability, performance, or uptime issues with an application.

Open Source Projects
--------------------
`statsd <https://github.com/etsy/statsd/>`_ is a node.js network daemon that
listens for metrics and aggregates them for transfer into another service
such as Graphite.

`Graphite <https://graphite.readthedocs.org/en/latest/overview.html>`_ stores
time-series data and displays them in graphs through a web application.

Monitoring Resources
--------------------
`The Virtues of Monitoring <http://www.paperplanes.de/2011/1/5/the_virtues_of_monitoring.html>`_

`Effortless Monitoring with collectd, Graphite, and Docker <http://blog.docker.io/2013/07/effortless-monitoring-with-collectd-graphite-and-docker/>`_

