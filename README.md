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
- 引用规范:`![显示文字](./Image_%y-%m-%d_%h-%n-%s '提示文字')`
  - %h：文件ID
  - %n：文件图片ID
  - %s：文件图片冗余ID(建议为60)


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

- Github图床+CDN加速
  - https://cdn.jsdelivr.net/gh/Sky_seeker/Pictrue_Bed/
  ![](https://cdn.jsdelivr.net/gh/Sky_seeker/Pictrue_Bed/img/2020/Image_2020-04-13_22-01-00.jpg)

- Backblaze B2云存储
  - https://f000.backblazeb2.com/file/Pictrue-Bed/
  ![](https://f000.backblazeb2.com/file/Pictrue-Bed/img/2020/Image_2020-04-13_22-01-00.jpg)
  
- 云存储+自定义域名
  - https://skyimg.ezyro.com/file/Pictrue-Bed/
  ![](https://skyimg.ezyro.com/file/Pictrue-Bed/img/2020/Image_2020-04-13_22-01-00.jpg)  
