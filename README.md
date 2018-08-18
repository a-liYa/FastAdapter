# FastAdapter

## 添加依赖

compile 'com.aliya:fast-adapter:1.0.0'

## 代码示例

```java
ListView mListView;

List<ListEntity> list = new ArrayList<>();

static {
    list.add(new ListEntity(MainActivity.class, "item - 示例"));
}

mListView.setAdapter(new FastAdapter(list));

```