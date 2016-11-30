# fs-xml-java-builder

Many people that came from Asterisk to FreeSWITCH complains about XML config files.

In fact, it is easier generate files in plain text than it is in XML.

I wrote some helper Java classes to minimize my problems with XML conf files.

Class XmlNode allow building a xml document in pure Java

Class Fs2Xml reads any FreeSwitch conf file and outputs the code necessary to recreate conf file with XmlNode.


