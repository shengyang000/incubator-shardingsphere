+++
toc = true
title = "解析器"
weight = 3
+++

ShardingSphere使用不同解析器支持SQL多种方言。对于未实现解析器的特定SQL方言，默认采用SQL92标准进行解析。

### 特定SQL方言解析器

- PostgreSQL解析器

- MySQL解析器

- Oracle解析器

- SQLServer解析器

注：MySQL解析器支持的方言包括MySQL、H2和MariaDB。

### 默认SQL方言解析器

其他SQL方言，如SQLite、Sybase、DB2和Informix等，默认采用SQL92标准进行解析。