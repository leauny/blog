### 代码块
#### 实现标题

``` py title="bubble_sort.py"
# py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### 实现行号

``` py linenums="1"
# py linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### 高亮

``` py linenums="11" hl_lines="2 4-6"
# py linenums="11" hl_lines="2 4-6"
# 可以看出linenums和hl_lines的行号无关
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

## 图表和emoji

:smile: (`:smile: `)

:fontawesome-regular-face-laugh-wink: (`:fontawesome-regular-face-laugh-wink:`)

:fontawesome-brands-twitter:{ .twitter } (`:fontawesome-brands-twitter:{ .twitter }`)

:octicons-heart-fill-24:{ .heart }(`:octicons-heart-fill-24:{ .heart }`)
