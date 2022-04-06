# mewcraft-resourcepack

该项目存放上古时代 Minecraft 服务器的资源包文件。

## 项目文件说明

```
assets
 └ armors (盔甲材质)
 └ minecraft (Minecraft 自有模型与材质)
 └ custom_entity (ItemsAdder 生物模型)
 └ mimaru (装饰资源 & 其他)
 └ mmoitems (MMOItems 相关内容)
 └ modelengine (ModelEngine 相关内容)
 └ pams (潘马斯相关内容)
 └ quests (任务标记相关内容)
 └ rpginventory (饰品栏GUI 相关内容)
 └ shields (盾牌)
 └ terraria (Terraria 相关内容)
 └ yass_furnitures (Yass 的家具)
 └ yass_itemshop (Yass 的售货架)
README.md (你现在看到的)
pack.mcmeta (资源包的元信息)
```

## Blockbench 开发事项

- 所有材质（textures）需要指定正确的命名空间（namespace），不可留空
- 如果可以，尽量导入 Minecraft 自己的材质文件以实现复用，降低维护成本