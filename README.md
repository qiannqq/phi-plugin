# phi-plugin

---

#### 介绍：
适用于 Yunzai-Bot V3 的 phigros 辅助插件

---

#### 安装：
在云崽目录下运行

```
//使用github
git clone https://github.com/Catrong/phi-plugin.git ./plugins/phi-plugin/
```
```
//使用gitee
git clone https://gitee.com/catrong/phi-plugin.git ./plugins/phi-plugin/
```

---

#### 功能
| 功能名称  |  功能说明  |
|-------| ----- |
| #rksacc|开始输入未输入的曲目acc|
| #rks结束|输入acc状态下有效，结束输入状态，可以进行查分|
| #rks修改 曲名|修改单曲acc|
| #rks|查询rks，目前会提供得出的phi1及b21结果，日后会加入推分建议、打歌统计等|
| #rks数据删除|删除本地个人数据|
| #phi曲xxx|查询phigros中某一曲目的图鉴，支持设定别名，支持修改图鉴格式|
| #phi设置别名 xxx ---> xxx|设置某一歌曲的别名，格式为 原名(或已有别名) ---> 别名（会自动过滤--->两边的空格）|
| #phi申请 xxx ---> xxx|向主人发出别名设置申请，格式没有限制，会将内容保存在 /data/tododata.yaml 中|
| #phi查询章节|发送曲目列表以章节进行分组的所有曲目信息，日后会增加其他分组方式|
| #phi随机(定数-定数)(AT IN HD EZ)|在指定范围内随机一首曲目，目前支持指定定数及难度，难度可多选|
| #phi计算等效rks [曲名] \| [acc] -[难度]|例：#phi计算等效rks 痉挛 \| 99 -IN ，可以计算等效rks|
| #phi计算推分rks [曲名] \| [acc] \| [当前rks]|例：#phi计算推分rks a0 \| 0 \| 14.56 -IN 或 #phi计算推分rks a0 （用于本地已有数据的用户）|

---

#### Todo
·写菜单

·写b19图

·...

---

#### 曲绘资源

https://wwvr.lanzouw.com/b0328fk4d
密码:ophi

---

## 免责声明

1. 功能仅限内部交流与小范围使用，请勿将Yunzai-Bot及phi-Plugin用于任何以盈利为目的的场景.
2. 图片与其他素材均来自于网络，仅供交流学习使用，如有侵权请联系，会立即删除.

---

#### 写的不好，轻喷……


