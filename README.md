# MineCraftPythonData
> 我的世界中国版 Python 方块和物品数据信息

### 使用前须知
> 所有的数据都是来自我的世界官方附加包内，对应的版本为 Minecraft Version 1.19.2.2

> modBlock.py 原版方块数据

> modItem.py 原版物品数据

### 特别提示
> 目前 modItem.py 内的数据内含有 modBlock.item，这个不是 Bug，所以如果在判断当前手持物品是否为原版物品时，应该使用以下代码：
```python
if itemName in modItem.ItemList and not in modBlock.BlockList:
  ...省略逻辑代码
```
