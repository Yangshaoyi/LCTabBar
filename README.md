# LCTabBar
自定义tabbar样式，中间凸起按钮，可以为3个或者5个tab栏

使用的时候直接在自定义TabBarController里面直接添加进去就可以了，方便使用。
主要调用代码：

LCTabBar *tab = [LCTabBar instanceCustomTabBarWithType:LCItemUIType_Five];

tab.centerBtnIcon = @"sou_00";

tab.tabDelegate = self;

[self setValue:tab forKey:@"tabBar"];


样式图:

![image](https://github.com/Yangshaoyi/LCTabBar/blob/master/project_image.jpg)
￼￼
