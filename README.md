# LiTiaotiao-Custom-Rules
李跳跳自定义规则

# 简介
本项目收集适用于“李跳跳”的 app 自定义规则，包括**普通规则**和**增强规则**。
- 普通规则：去除应用内广告、更新弹窗、青少年模式弹窗、打开通知提示等
- 增强规则：自动点击等

# 如何使用

1. 找到你想要应用规则的app包名；
2. 根据包名在本项目中查找对应规则文件。例如：包名以 “tv” 开头，请在文件夹 T 内查找，对于以 “cn”, “com” 开头的包名，统一存储在文件夹 C 下的 cn, com 子文件夹中；
3. 复制你想要的规则；
4. 打开“李跳跳”，点击 更多 -> 设置，找到需要应用规则的 app，长按 app 图标，粘贴复制的规则，点击保存。

## 点击下方包名首字母或前缀快速查找
- [A](./A/readme.md)
- [B](./B/readme.md)
- [C](./C/readme.md)
    - [cn](./C/cn/readme.md)
    - [com](./C/com/readme.md)
        - [com.A*xxx*](./C/com/com.A/readme.md)
        - [com.B*xxx*](./C/com/com.B/readme.md)
        - [com.C*xxx*](./C/com/com.C/readme.md)
        - [com.D*xxx*](./C/com/com.D/readme.md)
        - [com.E*xxx*](./C/com/com.E/readme.md)
        - [com.F*xxx*](./C/com/com.F/readme.md)
        - [com.G*xxx*](./C/com/com.G/readme.md)
        - [com.H*xxx*](./C/com/com.H/readme.md)
        - [com.I*xxx*](./C/com/com.I/readme.md)
        - [com.J*xxx*](./C/com/com.J/readme.md)
        - [com.K*xxx*](./C/com/com.K/readme.md)
        - [com.L*xxx*](./C/com/com.L/readme.md)
        - [com.M*xxx*](./C/com/com.M/readme.md)
        - [com.N*xxx*](./C/com/com.N/readme.md)
        - [com.O*xxx*](./C/com/com.O/readme.md)
        - [com.P*xxx*](./C/com/com.P/readme.md)
        - [com.Q*xxx*](./C/com/com.Q/readme.md)
        - [com.R*xxx*](./C/com/com.R/readme.md)
        - [com.S*xxx*](./C/com/com.S/readme.md)
        - [com.T*xxx*](./C/com/com.T/readme.md)
        - [com.U*xxx*](./C/com/com.U/readme.md)
        - [com.V*xxx*](./C/com/com.V/readme.md)
        - [com.W*xxx*](./C/com/com.W/readme.md)
        - [com.X*xxx*](./C/com/com.X/readme.md)
        - [com.Y*xxx*](./C/com/com.Y/readme.md)
        - [com.Z*xxx*](./C/com/com.Z/readme.md)
- [D](./D/readme.md)
- [E](./E/readme.md)
- [F](./F/readme.md)
- [G](./G/readme.md)
- [H](./H/readme.md)
- [I](./I/readme.md)
- [J](./J/readme.md)
- [K](./K/readme.md)
- [L](./L/readme.md)
- [M](./M/readme.md)
- [N](./N/readme.md)
- [O](./O/readme.md)
- [P](./P/readme.md)
- [Q](./Q/readme.md)
- [R](./R/readme.md)
- [S](./S/readme.md)
- [T](./T/readme.md)
- [U](./U/readme.md)
- [V](./V/readme.md)
- [W](./W/readme.md)
- [X](./X/readme.md)
- [Y](./Y/readme.md)
- [Z](./Z/readme.md)

# 说明
本项目欢迎贡献规则，贡献规则时请参考 [模版](template.md) 新增或修改规则。具体操作如下：

## 新增未收录 app 的自定义规则
1. 根据包名首字母进入相应的文件夹中，如包名以 “cn”，“com” 开头，需再次进入 C 文件夹的对应 cn, com 子文件夹中，然后新建一个子文件夹，名称与包名一致；
2. 在新创建的子文件夹中，创建 readme.md 文件，如有必要，还可以创建 assets 文件夹，用于存放 readme.md 使用的截图文件；
3. 复制 [模版](template.md) 全部内容到新创建的 readme.md 文件中，进行相应修改；

## 新增已收录 app 的自定义规则
1. 根据包名找到对应文件夹内的 readme.md 文件；
2. 打开 readme.md 文件，请先查找是否已经存在你要新增的规则，若不存在，请新增一条，请在代码块、详细说明列表、详细说明具体内容中新增对应内容
3. 请勿新增重复的规则

## 修改已收录 app 的自定义规则
1. 根据包名找到对应文件夹内的 readme.md 文件；
2. 打开 readme.md 文件，查找需要更新的规则，修改相应内容

## 删除已收录 app 的自定义规则

⚠**注意：一般情况下，请勿删除已有的规则，不同版本的 app，规则可能不完全一致，最大限度保留已有规则，以适用于大多数版本的 app。**

若您认为某条规则可能是错误提交的，并不适用于此 app 的任何版本，或者某条规则影响到了 app 的正常使用，可以删除对应规则。

附：[李跳跳进阶指南](https://juejin.cn/post/6938590373740544007)