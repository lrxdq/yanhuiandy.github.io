---
layout: post
title: Software crack
date: 2018-02-05
tags: Crack
---

<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=gb2312" />
<title>密码保护相应页面</title>
</head>
<body>
<SCRIPT LANGUAGE="JavaScript">
function password() {
var testV = 1;
var pass1 = prompt('🤔此页面只有熟悉的人员才可以浏览哦😜，请输入密码:','');
while (testV < 3) {
if (!pass1) 
history.go(-1);
if (pass1 == "andysoftware") {
alert('🙃一看就是熟悉我的人员😘!');
break;
} 
testV+=1;
var pass1 = 
prompt('🤣密码错误，此页面只有熟悉的人员才可以浏览哦🤗:');
}
if (pass1!="password" & testV ==3) 
history.go(-1);
return " ";
} 
document.write(password());
</SCRIPT>
</body>
</html>


### [UltraEdit for Mac](http://www.ultraedit.com/downloads/uex.html#macreq)
   >* 破解方法：-->终端运行，仅限18.00.0.19破解
   ```
   printf '\x31\xC0\xFF\xC0\xC3\x90' | dd seek=$((0x777160)) conv=notrunc bs=1 of=/Applications/UltraEdit.app/Contents/MacOS/UltraEdit
   ```



### 注

  >* ⚠️ [转载请注明原博客地址【https://yanhuiblog.tk】Andy所作,谢谢合作！](https://yanhuiandy.github.io/)


