# 根据时间点创建实例

MongoDB 控制台提供了根据时间点创建实例的功能，您可以根据某一实例的备份数据时间点创建新的实例。

## 注意事项

- 新实例创建过程中请勿删除使用的备份问题，否则会创建失败。
- 新实例所在地域只能与源实例地域一致。
- 新实例所选存储空间不应小于源实例，否则可能导致创建失败。

## 操作步骤

1. 登录 [MongoDB 控制台](https://mongodb-console.jdcloud.com/mongodb)。
2. 在实例列表页面，选择目标实例，点击实例名称，进入实例详情页面。
3. 在实例详情页面，点击右侧操作项中“根据时间点创建”，打开创建实例页面。
4. 选择要使用的备份，在操作项中点击“根据备份创建”，进入根据备份创建实例页面。

   ![](https://github.com/jdcloudcom/cn/blob/master/image/mongodb/mongo-036.png)

5. 在创建实例页面，选择计费类型、实例规格配置等信息，完成实例创建。创建过程同 [创建实例 ](https://github.com/jdcloudcom/cn/blob/master/documentation/Cloud-Database-and-Cache/MongoDB/Getting-Started/CreateInstance.md)。

   ![](https://github.com/jdcloudcom/cn/blob/master/image/mongodb/mongo-036.png)

## 相关参考

- [手动创建备份](https://github.com/jdcloudcom/cn/blob/master/documentation/Cloud-Database-and-Cache/MongoDB/Operation-Guide/Backup/CreateBackup.md)
- [根据备份创建实例](https://github.com/jdcloudcom/cn/blob/master/documentation/Cloud-Database-and-Cache/MongoDB/Operation-Guide/Backup/CreateInstance2.md)

