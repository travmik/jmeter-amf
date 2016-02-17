 JMeter AMF Plugin
---

Welcome to the JMeter-AMF Plugin Project. This plugin gives JMeter the ability to load test applications 
using the AMF3 protocol. Main features:

* Record AMF and HTTP traffic with the AMF Proxy Server
* Translate AMF to XML for easy manipulation
* Use variables to provide each virtual user with unique Client and Session IDs
* Store response XML in a variable for assertion and value extraction
* Review AMF responses as XML

Did this project save your company a few bucks or a few man hours? Want to encourage me to add a new feature? 
Just feel like buying me a beer? Please donate to help keep it going. 
https://github.com/steeltomato/jmeter-amf/wiki/Donate

 Requirements
---

* JMeter 2.6+
* BlazeDS libraries
* Optional: JAR containing all classes used for remoting
  * Provides cleaner, more reliable XML

 Installation
---

1. Click Downloads and grab the latest JMeter-AMF package.

2. Copy JMeter-AMF.jar to jmeter/lib/ext.

3. Download BlazeDS and copy blazeds-common.jar and blazeds-core.jar to jmeter/lib/ext.
  * http://opensource.adobe.com/wiki/display/blazeds/Downloads

 Credits
---

This project was created and is maintained by Kenneth Hill (kennethjhill@gmail.com)

Special thanks to the Apache Software Foundation and the contributors of the 
Jakarta JMeter project. Without your hard work, this project obviously wouldn't be possible.

Copyright 2011 the original author or authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
