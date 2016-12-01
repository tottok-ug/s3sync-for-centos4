s3sync-for-centos4
===

centos4系に awscliもs3cmdも入れづらい。
rubyとpythonのバージョンも古いし、、、、

だから、これ使って

## How to 
設定ファイル
```
AWS_ACCESS_KEY=HOGEHOGEFUGAGFUGA
AWS_SECRET_ACCESS_KEY=hogehogefugafuga
```

設定ファイル優先順位
```
1. ~/.s3sync-for-centos4
2. /etc/s3sync-for-centos4
```
  
```
$ s3sync-for-centos4 SOURCE_PATH s3://DEST_PATH
```


