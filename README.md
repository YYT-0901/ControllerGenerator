# 根据数据库格式生成后端工具

- 各种类
- Mapper
- MapperXML
- Service
- ServiceImpl
- Controller
- Comment(代码注释)
- 对字符串进行模糊搜索(Fuzzy)

## 接口生成

`/表名/loadDataList`

获取分页后数据

| 参数名   | 说明             |      |
| -------- | ---------------- | ---- |
| pageSize | 一页显示几个数据 |      |
| pageNo   | 显示第几页       |      |



`/表名/add`

添加数据

| 参数名                     | 说明 |      |
| -------------------------- | ---- | ---- |
| 转换为驼峰命名的数据库列名 |      |      |



`/表明/addBatch`

批量新增



`/表名/addOrUpdateBatch`

批量新增或修改



`/表明/get{驼峰表名}By{主键}`(s)



`/表明/update{驼峰表名}By{主键}`(s)



`/表明/delete{驼峰表名}By{主键}`(s)



---

学习视频: https://www.bilibili.com/video/BV1EN4y1c7sL/