
### vavr tree
```java
@Override  
public io.vavr.collection.List<Tree.Node<TestTypeEntity>> tree() {  
List<TestTypeEntity> list = listUsedOfStatus();  
list.stream().map(e -> {  
if (ObjectUtil.equal(e.getParentId(), 0)) {  
e.setParentId(null);  
}  
});  
return Tree.build(list, TestTypeEntity::getId,TestTypeEntity::getParentId);  
}
```

### hutool tree