# FUCK_HENUDC

### 使用方法：

#### 0.（懒人）点右上角的FORK，fork到你的仓库里

注意：这个方法会导致你配置的yml别人也能下到，不怕别人知道你学号的上

#### 0.（安全）打开你自己的GitHub首页，新建项目并克隆我的源码。小白请按照：网页链接

#### 1.收集信息

- #### 验证你的河大账号和密码：[点击链接](https://ids.henu.edu.cn/)并用你的学号登录，记住你登陆成功的学号和密码。

- #### 确认你的地址：[点击链接](https://lbs.qq.com/tool/getpoint/index.html)并选择你经常签到的地址。如：34.810703,114.369221 河南省开封市顺河回族区琢玉路。

- #### 记录你的skey：[点击链接](http://sc.ftqq.com/?c=code)微信登录后复制您的SCKEY代码

- #### 安卓手机额外步骤，为了您作弊不被发现，您可以在安卓手机上用今日校园APP扫描以下二维码：

  ![image](./pic/qrcode.png)

  #### 复制生成的文字，注意，粘贴时请不要粘贴文字尾部的：cpdaily/8.2.17 wisedu/8.2.17

#### 2.编辑config.yml

```yaml
enable: 1 #请将0改为1否则无法使用
ua: '这里填写你的UA，否则就用我的UA'
useserverchan: 1
serverchankey: '这里填写你的skey'
usecookies: 0
cookies: 
#username 学号或者工号
username: '这里填写学号'
#password 密码
password: '这里填写密码'
#address 地址，定位信息  中国河南省xx市xx区xx路
address: '这里填写中国＋你获取到的地址'
#school 学校全称
school: '河南大学'
#lon 填写你的经度，精确到小数点后五位，一定一定一定！
lon: '114.36922'
#lat 填写你的纬度，精确到小数点后五位，一定一定一定！
lat: '34.81070'
#校内填0校外填1
isMalposition: 0
#abnormalReason 反馈信息，不要填
abnormalReason:
#photo 签到照片，不要填
photo:
```

#### 3.鸣谢：

##### 感谢[@ZimoLoveShuang](https://github.com/ZimoLoveShuang) 提供80%的过程和源代码，本项目就是在他的[auto-sign](https://github.com/ZimoLoveShuang/auto-sign)基础上简单修改而来，有空帮他点个star吧~