# mewcraft-resourcepack

该项目存放上古时代 Minecraft 服务器的资源包文件。

## 命名空间说明

参考：[制表符](https://www.fuhaoku.net/zhibiao.html)

以下只列出了相对重要的命名空间，未列出短期内不会有更新的命名空间。

```
assets
 └ minecraft (Minecraft 自有模型与材质)
 └ terraria (Terraria 相关内容)
 └ mmoitems (MMOItems 相关内容)
 └ armors (盔甲材质)
 └ mimaru (装饰资源)
 └ custom_entity (ItemsAdder 生物模型)
 └ modelengine (ModelEngine 相关内容)
README.md (你现在看到的)
pack.mcmeta (资源包的元信息)
```

## Blockbench 开发事项

- 所有材质（textures）需要指定正确的命名空间（namespace），不可留空
- 如果可以，尽量导入 Minecraft 自己的材质文件以实现复用，降低维护成本