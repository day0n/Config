# Config

[TOC]

内容介绍：我的部分个人配置

#### gitconfig

解决部分人22端口无法访问的问题，对此，github提供了一种解决方案，允许你使用443端口进行ssh连接，因为443端口是访问https网站所必须的，大部分防火墙都会允许通过，但如果使用代理服务器可能产生干扰。

run this code,看看是否有成功提示，如果成功，则可以使用这个解决方案

```
ssh -T -p 443 git@ssh.github.com
```

那么你可以修改 ~/.ssh/config中的代码和我的config代码一样。

#### Vimconfig

修改你的用户目录下的.vimrc文件。~为用户目录.
