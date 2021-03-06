# 实验六

## 一、实验目标

1. 理解系统交互
2. 掌握UML顺序图的画法
3. 理解对象交互的定义与建模方法

## 二、实验内容

1. 观看教学视频，学习交互建模知识
2. 根据用例模型和类模型，确定功能所涉及的系统对象
3. 在顺序图上画出参与者（对象）
4. 在顺序图上画出消息（交互）

## 三、实验步骤

1. 使用哔哩哔哩网站，观看和学习交互建模知识
2. 根据用例模型和类模型，确定功能所涉及的系统对象
3. 根据 发布帖子 的用例规约设计：
	- 参与者(actor)：用户
	- M：帖子的编号的内容（帖子类）、用户的账号和密码（用户类）
	- V：发布帖子的界面、展示帖子的首页界面
	- C：发布帖子的控制器
	- 消息(message)：发布帖子-用例规约里的步骤
4. 根据 删除帖子 的用例规约设计：
	- 参与者(actor)：用户
	- M：帖子的编号的内容（帖子类）、用户的账号和密码（用户类）
	- V：删除的目标帖子的界面、展示已发布的所有帖子的界面
	- C：删除帖子的控制器
	- 消息(message)：删除帖子-用例规约里的步骤
5. 根据 注销账户 的用例规约设计：
	- 参与者(actor)：用户
	- M：用户的账号和密码（用户类）、用户的登陆状态和时间等记录（用户登陆记录类）
	- V：个人信息的界面、登录的界面
	- C：注销账户的控制器
	- 消息(message)：注销账户-用例规约里的步骤

## 四、实验结果
1. 画图  

![发布帖子的顺序图](./pn.jpg)  
图1. 发布帖子的顺序图  
  
![删除帖子的顺序图](./dn.jpg)  
图2. 删除帖子的顺序图  
  
![注销账户的顺序图](./la.jpg)  
图3. 注销账户的顺序图
