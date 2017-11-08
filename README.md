### test_for_multi_ssh
本地有多个ssh pk，通过配置git config看看是否可以实现不同user commit

测试通过，看commit历史记录

进入到git clone后的repo中后，通过设置git config --local user.email "dml..."可以区分commit用户，也就是会通过github登录邮箱来判断commit用户，git config中的user.name暂时看无关紧要，可以不改

可参考：[https://iamyz.com/blog/2017/11/05/%E7%94%9F%E6%88%90%E7%A7%98%E9%92%A5%E5%AF%B9ssh-keygen/](https://iamyz.com/blog/2017/11/05/%E7%94%9F%E6%88%90%E7%A7%98%E9%92%A5%E5%AF%B9ssh-keygen/)
