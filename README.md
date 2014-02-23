email-xml
=========

E-Mail XML-Schema (XSD) Specification

This specification does not address that layer of complexity.

Example:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<E-Mail>
    <Version>1.0</Version>
	<Message-ID>C60C5C82-9910-0001-0057-19301EBDA400</Message-ID>
	<Date>2001-12-17T09:30:47.0Z</Date>
    <From>
        <Address>from@domain.com</Address>
        <Name>Firstname1 Lastname1</Name>
    </From>
    <To>
        <Address>to@domain.com</Address>
        <Name>Firstname2 Lastname2</Name>
    </To>
    <Subject>My Subject</Subject>
    <Body Content-Type="text/html">base64Binary</Body>
</E-Mail>          

```

Links:<br>
http://www.molengo.com/emailxml/title/email-xml-schema-xsd
