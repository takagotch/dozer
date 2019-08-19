### dozer
---
https://github.com/DozerMapper/dozer/

```java
SourceClassName sourceObject = new SourceClassName();
sourceObject.setYourSourceFieldName("Dozer");

Mapper mapper = DozerBeanMapperBuilder.buildDefault();
DestinationObject destObject = mapper.map(sourceObject, DestinationClassName.class);

assertTrue(destObject.getYourDestinationFieldName().equals(sourceObject.getYourSourceFieldName()));
```

```
```

```
```


