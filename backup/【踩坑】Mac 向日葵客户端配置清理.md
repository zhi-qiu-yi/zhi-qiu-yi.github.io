Mac 客户端锁定了，各种密码输了个遍，都提示 “密码错误”，接近奔溃：

![image](https://github.com/zhi-qiu-yi/zhi-qiu-yi.github.io/assets/32633065/895ed700-03d3-4055-834c-7e989e8475b9)

[官方文档](https://service.oray.com/question/1659.html)有提到，客户端卸载重装就可以了，但是问题就在这一步，重装后依然是锁定状态，有些配置文件没有清理干净，官方文档并没有提到 Mac 端怎么清理，用 AppCleaner 也没清理掉对应的配置文件。

最后发现罪魁祸首是 `/etc/orayconfig.conf`，相关帖子：https://hk.v2ex.com/t/1028229