# Aciton-Rclone

gd两个团队盘之间自动同步备份，防翻车

secrets设置

`RCLONE_CONFIG`
```
[src]
type = drive
scope = drive
service_account_file = ./sa/0.json
service_account_file_path = ./sa/
team_drive = 

[dst]
type = drive
scope = drive
service_account_file = ./sa/0.json
service_account_file_path = ./sa/
team_drive = 

```


`SOURCE_DEST`
```
source:sourcepath dest:destpath
```
