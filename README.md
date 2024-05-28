# FairyGUI-unreal5

官方插件地址：https://github.com/fairygui/FairyGUI-unreal
官方示例地址：https://github.com/fairygui/FairyGUI-unreal-example

这个插件基于FairyGUI官方版本，没有做任何逻辑功能上的修改，单纯只是为了能使其在UE5上使用使用了新的API。
有些修改可能会存在不合理，但本着不做过多调整能跑就行的理念进行的。


如果你使用FairyGUI官方的FairyGUI-unreal-example这个项目来验证该插件，请注意将 Texture 的 CompressionSettings 改为 UserInterface2D（RGBA） 否则会出现图片加载问题（FairyGUI官方UE4项目过旧迁移到UE5这项会失效，所以需要手动调整一次）

![Alt text](image.png)

