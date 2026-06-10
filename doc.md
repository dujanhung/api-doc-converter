# the MD regex converter language

# <code>◆◇</code>

```txt
◆
input texts
◇
```

represents an abitrary text content.

# <code>▣</code>

```
▣
◆
metadata texts
◇
```

represents a metadata.

> [!NOTE]
> metadatas would be ignored at runtime.

# <code>◙</code>

```
◙
◆
input texts
◇
```

represents an input text regex from a MD file.

# <code>▼▲</code>

```txt
▼
▣
◙
◘
▲
```

represents an entry.

# <code>▶◀</code>

```txt
▶◀
```

represents a variable.