vlmcsd
======

KMS Emulator in C for openwrt.

http://forums.mydigitallife.info/threads/50234-Emulated-KMS-Servers-on-non-Windows-platforms

##Windows �������

CD ��%SystemRoot%\SYSTEM32��

CSCRIPT /NOLOGO SLMGR.VBS /SKMS 192.168.0.xxx

CSCRIPT /NOLOGO SLMGR.VBS /ATO

CSCRIPT /NOLOGO SLMGR.VBS /XPR

##Office/Project/Visio 2013(2010���°�װ·��) �������

32λ��CD ��%ProgramFiles(x86)%\MICROSOFT OFFICE\OFFICE15��

64λ��CD ��%ProgramFiles%\MICROSOFT OFFICE\OFFICE15��

CSCRIPT OSPP.VBS /SETHST:192.168.0.xxx

CSCRIPT OSPP.VBS /ACT

CSCRIPT OSPP.VBS /DSTATUS