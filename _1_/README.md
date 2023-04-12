# dump 따기
```
mysqldump -h [host_addr] -u [user_name] -p [database_name] > [dump_file_name].sql
```

# dump 먹이기
```
mysql -h [host_addr] -u [user_name] -p [db_name] < [dump_file_name].sql
```
