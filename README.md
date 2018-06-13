# 2018worldcupicalendar

> 2018世界杯全部赛程的日历文件。

IOS设备用户可以通过使用Safari浏览器打开[链接](
https://github.com/ontheway01/2018worldcupicalendar/edit/master/2018worldcup.ics),将世界杯赛程添加到IOS日历软件中。

或者直接微信扫描二维码，然后使用Safari打开二维码指向的链接。

![QR code](https://github.com/EugeneLiu/2018worldcupicalendar/blob/master/qrcode.png?raw=true)

效果如下：

![preview](https://github.com/EugeneLiu/2018worldcupicalendar/blob/master/preview.jpg?raw=true)

# 小组赛后动态更新

# [ics格式说明](https://en.wikipedia.org/wiki/ICalendar)

```
BEGIN:VCALENDAR #日历开始														
VERSION:2.0 #遵循的iCalendar 版本号
PRODID:-//2018 worldcup//2018 worldcup 1.0//CN #软件信息
METHOD:PUBLISH #方法：公开 也可以是 REQUEST 等用于日历间的信息沟通方法
X-WR-CALNAME:2018 World Cup #这是一个通用扩展属性 表示本日历的名称
X-WR-TIMEZONE:Asia/Shanghai #通用扩展属性，表示时区
BEGIN:VEVENT #事件开始
SUMMARY:俄罗斯🇷🇺 vs 🇸🇦沙特阿拉伯 #简介 一般是标题
DTSTART;VALUE=DATE-TIME:20180614T150000Z #开始的日期时间
DTEND;VALUE=DATE-TIME:20180614T170000Z #结束的日期时间
DTSTAMP;VALUE=DATE-TIME:20171212T235214Z #有Method 属性时表示 实例创建时间，没有时表示最后修订的日期时间
CLASS:public #保密类型
DESCRIPTION:A组 #描述
LOCATION:莫斯科卢日尼基体育场 #地址
STATUS:CONFIRMED #状态 TENTATIVE 试探 CONFIRMED 确认 CANCELLED 取消
TRANSP:OPAQUE #对于忙闲查询是否透明 OPAQUE 不透明 TRANSPARENT 透明
UUID:b8edcba4e89343a18e41021dc8e3ba28 #UID
END:VEVENT #事件结束
END:VCALENDAR #日历结束
```
