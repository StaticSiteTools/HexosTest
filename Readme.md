# Hexos测试

## 概要

**项目**：https://github.com/StaticSiteTools/Hexos 

**测试资源**：

[HexosTest](https://github.com/StaticSiteTools/HexosTest) 

* Github
  * [HexosTest Public for TravisCI](https://github.com/StaticSiteTools/Hexos_Test) 
  * [HexosTest Public for Github Action](https://github.com/StaticSiteTools/Hexos_Test2) 
* Gitee
  * [HexosTest Public for TravisCI](https://gitee.com/KumaNNN/hexos_test) 
  * [HexosTest Public for Github Action](https://gitee.com/KumaNNN/hexos_test2) 
* Coding
  * [HexosTest Public for TravisCI](https://e.coding.net/kumaNNN/hexos_test/Hexos_Test.git) 
  * [HexosTest Public for Github Action](https://e.coding.net/kumaNNN/hexos_test2/Hexos_Test2.git) 



## 环境变量

### Travis

```yaml
HEXOS_CODING_BRANCH : master
HEXOS_CODING_PROJECT_TOKEN : •••••••••••••••• 
HEXOS_CODING_PROJECT_USER :•••••••••••••••• 
HEXOS_CODING_REF : e.coding.net/kumaNNN/hexos_test/Hexos_Test.git 
HEXOS_GITEE_BRANCH :master 
HEXOS_GITEE_REF :gitee.com/KumaNNN/hexos_test.git 
HEXOS_GITEE_TOKEN  :•••••••••••••••• 
HEXOS_GITEE_USER :•••••••••••••••• 
HEXOS_GITHUB_BRANCH : master 
HEXOS_GITHUB_REF  : github.com/StaticSiteTools/Hexos_Test.git 
HEXOS_GITHUB_TOKEN :•••••••••••••••• 
HEXOS_NOTICE_EMAIL :•••••••••••••••• 
HEXOS_U_EMAIL :HexoTestUser@163.com 
HEXOS_U_NAME :HexoTestUser 
TZ  : Asia/Shanghai
```



### Github Action

```yaml
HEXOS_CODING_PROJECT_TOKEN : ••••••••••••••••  
HEXOS_CODING_PROJECT_USER :••••••••••••••••  
HEXOS_GITEE_TOKEN  :••••••••••••••••  
HEXOS_GITEE_USER :••••••••••••••••  
HEXOS_GITHUB_TOKEN :••••••••••••••••  

#如下可放置到文件中
HEXOS_CODING_BRANCH : master
HEXOS_CODING_REF : e.coding.net/kumaNNN/hexos_test2/Hexos_Test2.git
HEXOS_GITEE_BRANCH :master 
HEXOS_GITEE_REF :gitee.com/KumaNNN/hexos_test2.git 
HEXOS_GITHUB_BRANCH : master 
HEXOS_GITHUB_REF  : github.com/StaticSiteTools/Hexos_Test2.git 
HEXOS_NOTICE_EMAIL :HexoTestUser@163.com  
HEXOS_U_EMAIL :HexoTestUser@163.com 
HEXOS_U_NAME :HexoTestUser 
TZ  : Asia/Shanghai
```

