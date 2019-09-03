## List内置操作的时间复杂度

|操作|时间复杂度|
|---|---|
|indexx[]|O(1)|
|index assignment(按索引方式赋值)|O(1)|
|append|O(1)|
|pop()|O(1)|
|pop(i)|O(n)|
|insert(i, item)|O(n)|
|del operator|O(n)|
|iteration(迭代)|O(n)|
|contains(in)|O(n)|
|get slice[x:y]|O(k)| **k表示x与y之间的距离**
|del slice|O(n)|
|set slice|O(n + k)|
|reverse(颠倒顺序)|O(n)|
|concatenate(串联)|O(k)|
|sort|O(nlogn)|
|multiply|O(nk)|


## Dict内置操作的时间复杂度

|操作|时间复杂度|
|---|---|
|copy|O(n)|
|get item|O(1)|
|set item|O(1)|
|delete item|O(1)|
|contains(in)|O(1)|
|iteration|O(n)|
