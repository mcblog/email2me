# email2me
通过服务器+php+mysql发送邮件来告诉我某些东西的状况
# 前置条件
centos服务器yum install sendmail mailx -y   相关教程可以参考https://www.cnblogs.com/zhanbing/p/10970149.html
并且有php、mysql、服务
# 邮件内容的更新
php+mysql的形式更新文本
# 服务器发送邮件的选择
服务器通过判断mysql中某一值来确定是否该发送邮件
# 日志
暂时不生成日志
