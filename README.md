## 一个社区项目
## 资料
https://spring.io/guides

[Github OAuth](https://developer.github.com/apps/building-oauth-apps/authorizing-oauth-apps//)

## 工具
模拟请求的工具
[OkHttp](https://square.github.io/okhttp/)

## 脚本
```sql
create table user
(
	id int auto_increment
		primary key,
	account_id varchar(255) null,
	name varchar(50) null,
	token char(36) null,
	gmt_create bigint null,
	gmt_modified bigint null
);


```
