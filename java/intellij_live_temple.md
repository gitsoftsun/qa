# Intellij Live Template

## FOR JAVA


### 方法体
>* key: mebody
>* 创建方法体的模板，这样在写代码的时候可以减少叛空以及异常catch处理。

```text

// 1. 判断参数是否为空
boolean invalid = $PARAM1$;
// 2. 定义返回结果
$PARAM2$ result = $PARAM3$;
if (invalid){
    LOGGER.warn("$METHODNAME$ 's param is invalid! $PARAMNAMES$ value: {}", JSON.toJavaString($PARAM4$));
    return result;
}
// 3. 具体处理逻辑
try {
    $PARAM5$
}catch(Exception e){
    LOGGER.error("ERROR when call $METHODNAME$ e: {}", e);
    return result;
}
LOGGER.info("$METHODNAME$'s result : {}", JSON.toJSONString(result));
return result;


```

