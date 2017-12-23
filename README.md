# ElasticSearch 5.x/6.x 工具类整理(Python版)

本项目基于Python2.7，elasticsearch依赖，实现基于ES 5.x的工具类整理；

主要涵盖了常见的CRUD的动作；统计基于数据分析的角度，对DataFrame数据结构的插入也做以归纳总结。

*注：该项目可在5.x或者6.x下均可使用，唯一需要注意的是：ES6以后，一个Index只能对应一个Type，并且在版本7之后，会剔除Type属性；所以在使用时需加注意。详见 [官方文档](https://www.elastic.co/guide/en/elasticsearch/reference/6.0/removal-of-types.html)。*

