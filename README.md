# 易码API - Python接口
## 1. 简介：
本python包旨在为[易码api](http://www.51ym.me/User/apidocs.html)提供一个python封装包，使调用变得更简单。
## 2. 使用方法：
### 2.1 安装
    pip install yima
### 2.2 导入
    import yima as ym
### 2.3 功能速览
#### 2.3.1 创建易码客户端实例

    client1 = ym.YMClient('username', 'password', 'token')

通过简单的一句代码，可以创建一个名为client1的易码客户端实例，其参数中：
- username 和 password 为必填项，token为选填项
- 如果没有填写token，那么客户端实例在初始化时会自动获取token并记录在客户端实例中，因此不用手动去官网下载token。

#### 2.3.2 基础功能

    client1.get

#### 2.3.3 增强功能

## 3. 版本历史
### 2019.1.23 - 版本 0.1.1
- 修复了依赖库中包含基础库“time”而导致pip install不成功的bug
### 2019.1.23 - 版本 0.1.0
- 添加易码api基础功能
- 第一次尝试发PyPI包，好紧张啊，会不会有潜规则啊
## 4. Bug反馈及功能需求添加
如果发现程序bug或功能不完善的地方，欢迎联系：yihua.zhou@outlook.com。

