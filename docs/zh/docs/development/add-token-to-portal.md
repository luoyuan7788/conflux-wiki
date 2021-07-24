# 添加CRC20代币到Portal的方法与步骤



## 背景

在日常使用**Conflux Portal**时，可能需要向他人转账CRC20代币或LP币对，但是Conflux Portal在初始安装状态时，除**CFX**外不会在其代币列表内包含任何CRC20代币。本教程目的是帮助用户能够利用Conflux Portal的添加代币功能将代币加入其Portal列表。



## 两种添加方法

- 基于Conflux Portal代币搜索框的添加方法：**添加已接入代币时常用**
- 基于智能合约地址的添加方法：**添加LP对和不知名代币时常用**



## 法1：直接搜索法

- 点击Portal左上角“三横”栏目

![image-20210716103011293](./figure/image-20210716103011293.png)

- 呼出账户信息栏目，发现除CFX外没有任何代币

![image-20210716103038844](./figure/image-20210716103038844.png)

- 点击添加代币

![image-20210716103138957](./figure/image-20210716103138957.png)

- 搜索您想添加的代币，此处以“cusdt”为例，输入cusdt，选中

![image-20210716103328821](./figure/image-20210716103328821.png)

- 点击下一步

![image-20210716103351860](./figure/image-20210716103351860.png)

- 点击“添加代币”按钮

![image-20210716103415041](./figure/image-20210716103415041.png)



## 法2：合约地址自定义添加代币

有时有的CRC20标准代币并未接入Conflux Portal，包括LP对，都可以通过合约地址方法添加如Conflux Portal列表。

此处我们将给出第一个例子：

- 利用FC合约地址通过**自定义添加法**将FC加入钱包代币列表

已知FC代币合约地址为：**cfx:achc8nxj7r451c223m18w2dwjnmhkd6rxawrvkvsy2**

- 在添加代币栏目，切换为“自定义代币”

![image-20210716104319166](./figure/image-20210716104319166.png)

- 将cfx:achc8nxj7r451c223m18w2dwjnmhkd6rxawrvkvsy2贴入“代币联系人地址”

![image-20210716104402703](./figure/image-20210716104402703.png)

- 点击下一步

![image-20210716104458816](./figure/image-20210716104458816.png)

- 点击“添加代币”

![image-20210716104522749](./figure/image-20210716104522749.png)

## 法3：合约地址自定义添加LP

以fc和moon的LP对为例：其合约地址为cfx:aca45uhpk2d1j7vf8y927mr79w4bzne0vyfg9muytu，下图来源于[Conflux Scan](https://confluxscan.io/address/cfx:aca45uhpk2d1j7vf8y927mr79w4bzne0vyfg9muytu)

![image-20210716104719710](./figure/image-20210716104719710.png)

- 在Conflux Portal中添加自定义代币：

![image-20210716104826729](./figure/image-20210716104826729.png)

- 最终添加成功

![image-20210716104851660](./figure/image-20210716104851660.png)