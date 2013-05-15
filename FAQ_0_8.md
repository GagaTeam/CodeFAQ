## 用户权限是如何划分的？

公开项目对所有人都可见， 私有项目只有项目主人和成员才能访问，具体权限划分如下

### 公开项目


角色 | 项目读权限 | 项目写权限 | 管理项目 | 派生项目 |提交合并请求 | 处理合并请求 | 提交Issue | 处理Issue | 编辑Wiki | 对提交、合并请求、Issue发表评论
------------ | ------------- | ------------
项目主人|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|
项目成员|![](images/ok.png)|![](images/ok.png)|![](images/cross.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|
其它用户 |![](images/ok.png)|![](images/cross.png)|![](images/cross.png)|![](images/ok.png)|![](images/ok.png)|![](images/cross.png)|![](images/ok.png)|![](images/cross.png)|![](images/cross.png)|![](images/ok.png)|

### 私有项目


角色 | 项目读权限 | 项目写权限 | 管理项目 | 派生项目 |提交合并请求 | 处理合并请求 | 提交Issue | 处理Issue | 编辑Wiki | 对提交、合并请求、Issue发表评论
------------ | ------------- | ------------
项目主人|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|
项目成员－开发者|![](images/ok.png)|![](images/ok.png)|![](images/cross.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|![](images/ok.png)|
项目成员－观察者 |![](images/ok.png)|![](images/cross.png)|![](images/cross.png)|![](images/ok.png)|![](images/ok.png)|![](images/cross.png)|![](images/ok.png)|![](images/cross.png)|![](images/cross.png)|![](images/ok.png)|
其它用户 |![](images/cross.png)|![](images/cross.png)|![](images/cross.png)|![](images/cross.png)|![](images/cross.png)|![](images/cross.png)|![](images/cross.png)|![](images/cross.png)|![](images/cross.png)|![](images/cross.png)|


### 关于的权限解释

对以上项目的权限详细解释如下

权限 | 解释
------------ | ------------
项目管理权限 | 创建、删除项目，修改项目设置， 转交项目给其它人，添加项目成员，管理项目成员的权限
项目读权限 | 通过git/ssh/https克隆项目，在线浏览项目
项目写权限 | 通过ssh/https对项目进行Push操作， 编辑文件

