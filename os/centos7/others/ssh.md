# SSH [《MHS 学习笔记》] -> [《CentOS7》]  (mhs2019.3.1)

- [连接超时]

## <span id="time-out">连接超时</span> [Top]
```
$ vi /etc/ssh/sshd_config
t> ClientAliveInterval 60
t> ClientAliveCountMax 30
$ systemctl restart sshd
```

##
[《MHS 学习笔记》]: https://mhsnet.github.io/note/ "《MHS 学习笔记》"
[《CentOS7》]: https://mhsnet.github.io/note/os/centos7/index.html "《CentOS7》"
[SSH]: https://mhsnet.github.io/note/os/centos7/ssh.html "SSH"

[连接超时]: https://mhsnet.github.io/note/os/centos7/index.html#time-out "连接超时(Time Out)"