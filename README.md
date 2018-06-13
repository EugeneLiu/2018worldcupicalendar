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
PRODID:-//Google Inc//Google Calendar 70.9054//EN #软件信息
VERSION:2.0 #遵循的 
iCalendar 版本号
CALSCALE:GREGORIAN #历法：公历
METHOD:PUBLISH #方法：公开 也可以是 REQUEST 等用于日历间的信息沟通方法
X-WR-CALNAME:yulanggong@gmail.com #这是一个通用扩展属性 表示本日历的名称
X-WR-TIMEZONE:Asia/Shanghai #通用扩展属性，表示时区
BEGIN:VEVENT #事件开始
DTSTART:20090305T112200Z #开始的日期时间
DTEND:20090305T122200Z #结束的日期时间
DTSTAMP:20140613T033914Z #有Method 属性时表示 实例创建时间，没有时表示最后修订的日期时间
UID:9r5p7q78uohmk1bbt0iedof9s4@google.com #UID
CLASS:PRIVATE #保密类型
CREATED:20090305T092105Z #创建的日期时间
DESCRIPTION:test #描述
LAST-MODIFIED:20090305T092130Z #最后修改日期时间
LOCATION:test #地址
SEQUENCE:1 #排列序号
STATUS:CONFIRMED #状态 TENTATIVE 试探 CONFIRMED 确认 CANCELLED 取消
SUMMARY: test #简介 一般是标题
TRANSP:OPAQUE #对于忙闲查询是否透明 OPAQUE 不透明 TRANSPARENT 透明
END:VEVENT #事件结束
END:VCALENDAR #日历结束
```
