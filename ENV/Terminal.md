### Terminal

```sh
sudo apt install net-tools openssh-server samba
sudo apt install vim
```

```
if [ "$TERM"="linux" ] ;then 
  export LANGUAGE=en_US 
  export LANG=en_US.UTF-8 
fi
```

|             变量             |                 功能                 |
| :--------------------------: | :----------------------------------: |
|       HandleLidSwitch        |      使用内置电池时，合盖的行为      |
| HandleLidSwitchExternalPower |      使用外接电源时，合盖的行为      |
|    HandleLidSwitchDocked     | 外接了拓展坞链接显示器时，合盖的行为 |

|    值     |    含义     |
| :-------: | :---------: |
|  suspend  |    挂起     |
|   lock    |    锁定     |
|  ignore   |   不动作    |
| poweroff  | 关机:shock: |
| hibernate |    休眠     |

```sh
sudo vi /etc/systemd/logind.conf
sudo service systemd-logind restart
```

