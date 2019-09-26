# SysinternalsSuite
## Adexploer - 域控info拓展 ##
登录之后即可查看到域的各种元数据  
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/ADExplorer.jpg)  
查找关键有效字段  
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/ADsearch.jpg)  
拍摄快照生成DAT文件，以便转移  
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/snipaste.jpg)  
## ADInsight ##
## AccessEnum - 文件权限管理 ##
查看目录下文件对所有用户的读写和deny权限  
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/access-D.jpg)  
也可以查看注册表的读写的和deny权限  
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/access-R.jpg)  
## Autologon - 自动登录 ##
自动登录使您可以轻松配置Windows的内置自动登录机制。Windows不用等待用户输入其名称和密码，而是使用您在Autologon中输入的凭据（在注册表中加密）自动登录指定的用户。  
自动登录很容易使用。只需运行autologon.exe，填写对话框，然后点击启用即可。要关闭自动登录，请点击禁用。同样，如果在系统执行自动登录之前按住Shift键，则该登录将禁用自动登录。您还可以将用户名，域和密码作为命令行参数传递  
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/autologon.jpg)   
感觉卵用不大  
## Autoruns ##
右键进程可以跳转到目录和注册表，还可以一键上传到VirTotal,也可以配合Process Explorer高效组合  
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/autoruns.jpg)   
可以查看所有用户，和查看指定用户的进程  
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/autoruns2.jpg)   
## Bginfo ##
嵌入式将以下信息的镶在桌面上  
Boot Time/CPU/Default Gateway/DHCP Server/DNS Server/Free Space/Host Name/IE Version/IP Address/Logon Domain/Logon Server/MAC Address/Machine Domain/Memory/Network Card/Network Speed/Network Type/OS Version/Service Pack/Snapshot Time/Subnet Mask/System Type/User Name/Volumes;  
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/BIginfo.jpg)   
可以设置字体颜色  
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/Biginfo%20color.jpg)   
可以选择嵌入位置，也用来记笔记、当备忘录使。
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/B.jpg)   
## Cacheset ##
CacheSet 允许您处理系统文件缓存中的工作集参数。CacheSet 可以在所有版本的 NT 上运行，而且在不对新 Service Pack 版本进行修改的情况下也可运行。除了使您能够控制工作集大小的最小值和最大值，它还允许您重置缓存的工作集，强制它在必要时从一个最小的起点开始增长。CacheSet 的更改会对缓存的大小立即产生影响。注意：要在 NT 4.0 Service Pack 4 上使用 CacheSet，您必须拥有“增加配额”的权限（管理员账户默认拥有此权限）
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/cache.jpg)   
## Clockres ##
查看计时器分辨率
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/clockres.jpg)   
## Contig ##
磁盘碎片整理工具
contig[-v] [-a] [-q] [-s] [文件名]
使用 -v 开关可以使 Contig打印出所执行的文件碎片整理操作的信息。如果您只希望看到一个或多个文件的碎片化程度，请使用 -a 开关令 Contig分析碎片。使用 –s 开关，可以在用通配符指定文件名时递归执行子目录处理。例如，要对 c:\winnt 下的所有 DLL 文件进行碎片整理，您可以输入“contig -s c:\winnt\*.dll”。-q 开关覆盖 -v 开关，使 Contig在“静默”模式下运行，此时碎片整理过程中打印出的唯一内容就是摘要信息。
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/contig.jpg)   
也可以使用GUI版本Power Defragmenter GUI.exe，需和contig在同一路径下使用，更加高效快捷，多任务并发
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/contigG.jpg)   
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/contigG1.jpg)   
## Coreinfo ##
可以提供有关处理器、组织结构和高速缓存拓扑的有用信息。可以逻辑显示处理器和物理内存之间的映射关系，此外还能显示NUMA节点、组、插槽以及所有级别的高速缓存  
用法如下
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/Coreinfo.jpg)   
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/Coreinfol.jpg)   
## Dbgview ##
## Desktops ##
## DiskView ##
## FindLinks ##
## Listdlls ##
## LoadOrd ##
## LoadOrdC ##
## Procmon ##
## PsExec ##
## PsGetsid ##
## PsInfo ##
## PsLoggedon ##
## PsService ##
## RAMMap ##
## RegDelNull ##
## ShareEnum ##
## ShellRunas ##
## Sysmon ##
## TCPVIEW ##
## Testlimit ##
## Volumeid ##
## Winobj ##
## Zoomlt ##
## accesschk ##
## adrestore ##
## ctrl2cap ##
## doskext ##
## du ##
## efsdump ##
## handle ##
## hex2dec ##
## junction ##
## ldmdump ##
## livekd ##
## logonsessions ##
## movefile ##
## notmyfault ##
## ntfsinfo ##
## pagedfrg ##
## pendmoves ##
## pipelist ##
## portmon ##
## procdump ##
## procexp ##
## psfile ##
## pskill ##
## pslist ##
## psloglist ##
## pspasswd ##
## psping ##
## psshutdown ##
## pssuspend ##
## regjump ##
## ru ##
## sdelete ##
## sigcheck ##
## stream ##
## string ##
## sync ##
## vmmap ##
## whois ##
======================================misc======================================
## BrowsingHistoryView ##
在以下浏览器历史记录中搜索指定字符“github”  
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/browsinghistory.jpg)   
即可查看到记录  
![image](https://github.com/mai-lang-chai/Sysinternals/blob/master/pic/browsinghistory1.jpg)   
