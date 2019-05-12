# ulaminer使用文档

## 快速上手

###首次打开

首次使用打开ulaminer，会弹出如下对话框：

![1557642539060](./images/set-global-crypto-code.png)

此代码就是在ulamchain.io上创建账户是输入的密码。必须填写。

``` python
>> 此对话框提示用户输入全局加密代码，此代码就是在ulamchain.io上创建账户是输入的密码，此密码会在批量创建账户时统一使用。如果用户拒绝填写此代码，对话框会一直弹出，且用户会被拒绝在ulaminer中新建账户。
```

#### 使用文件导入账户

适用于你已经有了ULAM账户，需要将账户导入Ulaminer时。点击创建账户按钮：

![xxxxxx](./images/create-new-accounts.png)

通过文件形式导入账户数据。文件导入可以下载样例文件。文件格式为微软的2010+的电子表格文件，扩展名为xlsx，Mac版本下使用Number另存文件为此格式也可以完成导入。

![1557644287823](./images/import-file.png)

导入文件样例如下，`请务必提供代理私钥`，会大大简化后续操作。

![1557644483969](./images/import-excel-example.png)

上传后，确认上传数据是否正确，如果检查无误，点击确认。

![1557644352842](./images/confirm-accounts-import.png)

账户导入后呈现在我的钱包主界面中。此时需要点击黑桃按钮（Spade），将当前添加的所有代理私钥都提交到矿机中开始挖矿。如果ULAM账户中有余额，挖矿工作自动开始。

![1557644732592](./images/commit-to-mining-cluster.png)

#### 账户自动切分与收割功能

新导入的账户默认是ULAM-2000分组，此时只需点击收割按钮。

![1557645062404](./images/power-on-off-harvest-engine.png)

选择收割策略。

![1557645267813](./images/schedule-harvest-engine.png)

点击确定后开始收割。

### 矿机使用

矿机使用时有两个概念：矿工组和挖矿节点(一个账户地址，亦即一个代理私钥被称为一个节点)。矿工组是为了用户管理方便，将大量的mambo分类并实施查看挖矿状态。

#### 新建矿工组

![1557645584952](./images/create-new-mining-owner.png)

点击矿场看板，将矿工组切换至刚刚创建的矿工组下，此时点击添加代理私钥按钮。



### 钱包使用

#### 转账

#### 账户切分与合并

#### 账户

##### 批量创建账户

适用于您还没有任何ULAM账户，需要在Ulaminer上创建账户，点击`我的钱包` 点击新建账户按钮

![1557642848259](./images/create-new-accounts.png)

弹出对话框中，Keystore加密代码就是刚才用户输入的代码，输入要创建账户的数量后，点击锤子标志创建。

![1557642986939](./images/create-new-accounts-batch.png)

点击创建后，对话框可以关闭，新建的账户的代理私钥自动生成，例如此时输入批量创建5个账户。点击创建。程序反应如下：

![1557643088542](./images/create-new-accounts-batch-react.png)

代理私钥自动生成，如下图所示。

![1557643140560](./images/create-new-accounts-batch-auto-apk.png)

此时账户中没有ULAM余额，需要外部通过其他途径充值ULAM账户。

##### 手动导入账户

通过粘贴输入框导入，格式如下，导入用户尽量提供代理私钥，否则会为后面操作带来困难。

![1557643892255](./images/import-accounts-manually.png)

点击确定后，弹出对话框，检查是否符合导入预期。

![1557644352842](./images/confirm-accounts-import.png)

如果符合预期则点击确定，如果有错误则修改重试。

#### 收割引擎相关

#### 私有数据相关

## 常见问题

### 我的私人数据是否安全？

### 

