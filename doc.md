# the regex converter language

## variants

### <code>◆◇</code>

```txt
◆
input texts
◇
```

represents an abitrary text content.

## keywords

### <code>▣</code>

```
▣
◆
metadata texts
◇
```

represents a metadata.

> [!NOTE]
> metadatas would be ignored at runtime.

### <code>◙</code>

```
◙
◆
input regexs
◇
```

represents a regex content from the input file.

### <code>◘</code>

```
◘
◆
output regexs
◇
```

represents a regex content from the output file.

## containers

### <code>▼▲</code>

```txt
▼
▣
◙
◘
▲
```

represents an entry container.

## regexs

### <code>▶◀</code>

```txt
▶var_name◀
```

represents an abitrary variable regex.

> [!NOTE]
> - `var_name` must be `^[A-Za-z\_\-]{1-255}$`