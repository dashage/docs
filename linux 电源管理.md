# linux 电源管理

## 合盖不休眠的设置方法

```
# vim /etc/systemd/logind.conf
	HandleLidSwitch=lock
# systemctl restart systemd-logind
```

