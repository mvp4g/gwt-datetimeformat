# gwt-i18n-cldr
GWT cldr classes generated from gwt-cldr-importer

### Dependencies

```xml
<dependency>
    <groupId>org.gwtproject.tools</groupId>
    <artifactId>gwt-datetimeformat</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
<dependency>
    <groupId>org.gwtproject.tools</groupId>
    <artifactId>gwt-datetimeformat</artifactId>
    <version>1.0-SNAPSHOT</version>
    <classifier>sources</classifier>
</dependency>
```

### Inherits

```xml
<inherits name="org.gwtproject.i18n.DateTimeFormat"/>
```

### Usage


```
DateTimeFormat format = DateTimeFormat.getFormat(new DateTimeFormatInfoImpl_en().dateFormatFull());

format.format(new Date()));
```
