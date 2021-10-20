# 用户手册

## 定制

如果想要自定义网址缩写，只需要在 {file}`/conf.py` 中修改 `extlinks` 变量：

```python
# 缩短链接
extlinks = {
    'daobook': ('https://daobook.github.io', 'Dao Book'),
    'xinetzone': ('https://xinetzone.github.io', 'xinetzone'),
}
```

:::{seealso}
详细内容可以参考：{mod}`sphinx.ext.extlinks`。
:::