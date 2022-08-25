工具概述：
Nacos未授权绕过漏洞图形化利用工具

漏洞概述：
Nacos官方在github发布的issue中披露Alibaba Nacos 存在一个由于不当处理User-Agent导致的认证绕过漏洞。通过该漏洞，攻击者可以进行任意操作，包括未授权创建新用户并进行登录后操作。

影响版本：
Nacos <= 2.0.0-ALPHA.1

修复建议：
升级nacos版本到2.0.4或者最新版本


漏洞利用可参考https://github.com/alibaba/nacos/issues/4593
