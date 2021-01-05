# 梦幻之心星的个人图床

## 注意事项
- 建议使用**复制**+**删除**操作来代替**移动**操作
- 移动操作只是修改文件的索引，不会创建文件副本
- 手动删除的文件可以通过数据恢复软件来找回
- Git删除的文件用数据恢复软件也很难找回


## 图片大小与命名

- 尺寸大小:建议不超过800x800
- 长宽比:建议比值在1~2之间
  - 推荐值： **3:2** ； **4:3** ； **5:3** ； **16:9**
- 命名规范:`Image_%y-%m-%d_%h-%n-%s`
- 修改规范：采用第一次定稿的日期，只允许修改`%s`且只能递增或递减
- 引用规范:`![显示文字](./Image_%y-%m-%d_%h-%n-%s '提示文字')`
  - %h：文件ID
  - %n：文件图片ID
  - %s：文件图片冗余ID(默认为60)

## 图片路径替换

- 本地临时路径
 `./${filename}/`
- 本地图床路径
 `G:/Pictrue_Bed/img/`
- 云端路径前缀(Github图床；CDN加速)(已废弃)(仅用于上传图片到微信)
 `https://cdn.jsdelivr.net/gh/Sky-seeker/Pictrue_Bed/img/`
- 云端路径前缀(Backblaze B2云存储)
 `https://f000.backblazeb2.com/file/Pictrue-Bed/img/`


## 图片网络地址有效性测试


- Github
  - https://github.com/Sky-seeker/Pictrue_Bed/blob/master/img/
  ![](https://github.com/Sky-seeker/Pictrue_Bed/blob/master/img/2020/Image_0000-00-00_00-00-00.jpg)

- Github图床+CDN加速
  - https://cdn.jsdelivr.net/gh/Sky_seeker/Pictrue_Bed/img/
  ![](https://cdn.jsdelivr.net/gh/Sky_seeker/Pictrue_Bed/img/2020/Image_0000-00-00_00-00-00.jpg)

- Backblaze B2云存储
  - https://f000.backblazeb2.com/file/Pictrue-Bed/img/
  ![](https://f000.backblazeb2.com/file/Pictrue-Bed/img/2020/Image_0000-00-00_00-00-00.jpg)
  
- 云存储+自定义域名
  - https://skyimg.ezyro.com/file/Pictrue-Bed/img/
  ![](https://skyimg.ezyro.com/file/Pictrue-Bed/img/2020/Image_0000-00-00_00-00-00.jpg)  


