# 选择角色界面

## 所含控件

- 角色列表（由角色名、种族、公会、等级和所在地区等信息组成）
- 进入游戏
- 退出游戏
- 创建角色
- 删除角色

## 初始化

- 获取账户中角色信息，并根据信息创建角色列表
- 将角色列表中第一项设置为选中项

## 点选角色

- 点选的角色设为列表选中项

## 选中项变更

当列表中选中项变更时，进行如下操作

- 根据选中角色信息更新BP_selectedAvatar
- 选中项高亮，取消选中项取消高亮

## 退出游戏

向服务器发送请求：登出服务器

## 进入游戏

获取当前选中角色，向服务器请求进入游戏

## 删除角色

获取当前选中角色，向服务器请求删除角色

## 创建角色

关闭选择角色界面，打开创建角色界面
