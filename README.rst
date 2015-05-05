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

License and Trademarks
----------------------

Copyright © 2015 Cask Data, Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except
in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the 
License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, 
either express or implied. See the License for the specific language governing permissions 
and limitations under the License.

Cask is a trademark of Cask Data, Inc. All rights reserved.

Apache, Apache HBase, and HBase are trademarks of The Apache Software Foundation. Used with
permission. No endorsement by The Apache Software Foundation is implied by the use of these marks.
