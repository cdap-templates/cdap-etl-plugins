==================
CDAP ETL Plugins
==================

This project includes some example plugins for the CDAP ETL Application Templates.
A plugin is an extension of a template that implements an interface expected by the template.
In the case of the ETL templates, plugins implement the BatchSource, RealtimeSource,
Transform, BatchSink, or RealtimeSink interface. They can then be deployed on the CDAP master
host and made available for use.

This project contains the following plugins.

Sources
-------

TwitterSource
+++++++++++++

A realtime source that reads data from the Twitter API

JmsSource
+++++++++

A realtime source that consumes from JMS 
