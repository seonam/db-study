
### Settings
```
create user study identified by "123";
grant create session, create table, create sequence, create view, create procedure to study;
alter user study quota unlimited on users;

# 이후 기존 local 스키마 duplicate 로 하고 user study, password 123 으로 접속하면 스키마가 하나 더 생긴다
```
