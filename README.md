# SpamAssassin_Chinese_rules

SpamAssassin AntiSpam Chinese rules 基于SpamAssassin的中文垃圾邮件过滤规则。

CERNET_Chinese_rules.cf 为CCERT反垃圾邮件研究小组推出的基于SpamAssassin的中文垃圾邮件过滤规则集Chinese_rules.cf。

WEVSTY_ZHCN_UTF8.cf 为本人基于CCERT的规则做出更新的规则。

MIME_Attachment_UTF8.cf 为附件识别的规则。

#使用方法

下载CERNET_Chinese_rules.cf 或 WEVSTY_ZHCN_UTF8.cf后规则放在SpamAssassin存放规则的目录(一般在 /etc/mail/spamassassin)之后重启SpamAssassin生效

#开发规则参考

>http://wiki.apache.org/spamassassin/WritingRules

>https://orangeassassin.readthedocs.io/en/latest/rule.types.html