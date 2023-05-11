# Import-Tools

Import-Tools is a web tool for migrating Jira data to ONES system. 


## Version Relationship
|  Tools Version   | ONES Version|Remark|
|  ----  | ----  |----|
| v1.x.x  | [3.13.10, 3.13.40] ||
| v2.x.x  | [3.13.41, 3.13.49] ||
| v3.x.x  | [3.13.50, ~)|recommended|



## Quick Start
### Step 1: login to jira server by ssh
### Step 2: download the latest binary file to jira server
### Step 3: tar file and run start.sh

```bash
ssh jira@jira server ip

tar -xvf import-tools-cn.tar.gz && ./scripts/start.sh
```

Then visit the website: http://jira-server-ip:port

## Mapping xlsx
[Jira migration mapping form.xlsx](https://github.com/BangWork/migration-tool-assets/raw/master/Jira%20migration%20mapping%20form.xlsx)

[Jira数据迁移清单.xlsx](https://github.com/BangWork/migration-tool-assets/raw/master/Jira%207.10%EF%BC%88Server%EF%BC%89%E6%95%B0%E6%8D%AE%E8%BF%81%E7%A7%BB%E6%B8%85%E5%8D%95.xlsx)

[Jira データ移行リスト.xlsx](https://github.com/BangWork/migration-tool-assets/raw/master/Jira%20%E3%83%86%E3%82%99%E3%83%BC%E3%82%BF%E7%A7%BB%E8%A1%8C%E3%83%AA%E3%82%B9%E3%83%88%E3%82%92%E3%82%BF%E3%82%99%E3%82%A6%E3%83%B3%E3%83%AD%E3%83%BC%E3%83%88%E3%82%99.xlsx)

