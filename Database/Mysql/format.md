### Mysql中varchar和longtext的区别？
- varchar为变长字节，所占空间为字符串实际长度加1，最长为65535个字节
- 而longtext也是变长字符存储，只保存字符数据，最长为4294967295字节，比较适合存储大内容
