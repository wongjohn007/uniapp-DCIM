# API 文档

## 属性

| 参数 | 说明 | 类型 | 可选值 | 默认值 |
| --- |------|:----:|-----|:-----:|
| action | 上传的服务器地址 | String | - | - |
| autoUpload | 是否自动上传 | Boolean | true,false | true |
| data | 上传的附加参数 | Object | - | {} |
| name | 上传文件字段名 | String | - | file |
| header | 上传头文件信息 | Object | - | {} |
| disabled | 是否禁用 | Boolean | - | false |
| iconColor | 图标颜色 | String | - | "#0099cc" |
| iconSize | 图标大小 | Number, String | - | 36 |



## Events

| 事件名 | 说明 | 参数 |
| ---- |-----| ----- |
| submit | 手动上传图片 | 图片地址路径 |


## Example

| 案例 |
| --------- |
| <ai-upload-image :src="imgUrl" action="127.0.0.1" iconColor="#0099cc" iconSize="36" @success="success" @fail="fail"></ai-upload-image> |