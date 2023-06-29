# Migration-Tool

Migration-Tool is a web tool for migrating Jira data to ONES system.
Migration-Tool will read the backup package directory and the attachment directory of Jira Server, which are located in Jira Local Home. 
It will not modify and delete jira server data.

- Jira Local Home (default): /var/atlassian/application-data/jira
- Backup package directory: Jira Local Home/export
- Attachment directory: Jira Local Home/data/attachments

---

## Version Relationship
|  Tools Version   | ONES Version|Remark|
|  ----  | ----  |----|
| v3.x.x  | [3.13.50, ~)|recommended|

---

## Mapping xlsx
> The following forms show how Jira data will be migrated to ONES (such as Jira project, user, issue, etc.)

Chinese version: [Jira数据迁移清单.xlsx](https://github.com/BangWork/migration-tool-assets/raw/master/Jira%207.10%EF%BC%88Server%EF%BC%89%E6%95%B0%E6%8D%AE%E8%BF%81%E7%A7%BB%E6%B8%85%E5%8D%95.xlsx)

English version: [Jira migration mapping form.xlsx](https://github.com/BangWork/migration-tool-assets/raw/master/Jira%20migration%20mapping%20form.xlsx)

Japanese version: [Jira データ移行リスト.xlsx](https://github.com/BangWork/migration-tool-assets/raw/master/Jira%20%E3%83%87%E3%83%BC%E3%82%BF%E7%A7%BB%E8%A1%8C%E3%83%AA%E3%82%B9%E3%83%88%E3%82%92%E3%83%80%E3%82%A6%E3%83%B3%E3%83%AD%E3%83%BC%E3%83%89.xlsx)

---
## Quick Start
### Step 1: Log into jira server by ssh
### Step 2: Download the zip file to jira server
### Step 3: Unzip file and run start.sh

```bash
ssh jira@jira-server-ip

unzip import-tools-*-*.zip && cd import-tools-*-* && ./scripts/start.sh
```

Then visit Jira migration tool by website: http://jira-server-ip:port
