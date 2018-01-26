
## 常用命令
命令格式： mvn  liquibase:命令名 
- update  应用变更到db 
- clearCheckSums  如果执行过的 changeSet 被修改，则校验和失败，无法继续，需这个命令修复
- dbDoc  产生DB变更历史的文档
- dropALl 清理，谨慎！只用于自己的测试DB！


## 参考
- maven pugin:
http://www.liquibase.org/documentation/maven/

- change log 配置：
http://www.liquibase.org/documentation/changes/

