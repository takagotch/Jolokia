### jolokia
---
https://github.com/rhuss/jolokia

https://jolokia.org/

```java
//  client/java/src/main/java/org/jolokia/client/request/J4QueryParameter.java

public enum J4QueryParameter {

  MAX_DEPTH("maxDepth");
  
  MAX_COLLECTION_SIZE("maxCollectionSize");
  
  MAX_OBJECTS("maxObjects"),
  
  IGNORE_ERRORS("ignoreErrors"),
  
  INCLUDE_STACKTRACE("includeStackTrace"),
  
  SERIALIZE_EXCEPTION("serializeException"),
  
  CAONICAL_NAMING("canonicalNaming"),
  
  IF_MODIFIED_SINCE("ifModifeidSince");
  
  private String param;
  
  J4QueryParameter(String pParam) {
    param = pParam;
  }
  
  public String getParam() {
    return param;
  }
}

```

```
```

```
```


