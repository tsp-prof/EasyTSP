##### README for Easy TSP

**使命**: 支持新能源车企以最小的成本和便捷的操作，完成GB/T32960相关的平台的认证业务（国家级与地方级）、车辆符合性认证业务、车辆接入业务与国家平台接入业务。

**mission**: support NEV OEM accomplishing China GB/T 32960 required-campaigns which include OEM Platform National and State Certification, NEV Compliance Certification,NEV Remote Service & Management, Integration with National & State Government NEV Centers in most Cost-Effective and Easy way from Building-Up to Maintainance

###### 功能 Features：
1. 国标规定的命令标识调试（适合初步平台联调，排查问题）  
   GB/T 32960 Defined Command Shakedown Test
2. 国标要求的平台符合性测试自动化  
   Platform Certification Test in Automatic Way
3. 国标合规的车辆接入与数据上报国家平台  
   NEV Remote Service & Management/Integration with National and State Government NEV Center
4. 内部国标数据源接入与数据上报国家平台（KAFKA）  
   Integration with KAFKA which is gathering NEV Data
5. 外部国标数据源接入与数据上报国家平台（外部平台）  
   Integration with 3rd Party TSP
6. 国标基准的车辆实时业务数据校验  
   NEV Data Validation in terms of GB/T 32960 
7. 国标报文合规的目标平台压测  
   Performance Test Client Tool for TSP
8. 政府平台（国家平台、地方平台或者其他第三方国标合规平台）转发白名单管理  
   NEV Whitelist Management for Forwarding Data to Government NEV Center
9. 实车实时数据整理、保存与统计（作为自动化测试的数据源）  
   NEV History Data Management

###### 运行 Deployment：
1. 使用本地默认语言运行  
   Run in Default Locale Language
    * java -jar EasyTSP-2.8.0-RELEASE.jar  
2. 使用特定语言运行。当前版本支持中、英、德、日、韩、阿拉伯6种语言。  
   Run in Specified Language which support Chinese,English,Germany,Japanese,Korean,Arabic
    * 中文 java -Duser.language=zh -jar EasyTSP-2.8.0-RELEASE.jar
    * English java -Duser.language=en -jar EasyTSP-2.8.0-RELEASE.jar
    * Deutsch java -Duser.language=de -jar EasyTSP-2.8.0-RELEASE.jar
    * 日本語 java -Duser.language=ja -jar EasyTSP-2.8.0-RELEASE.jar
    * 한국어 java -Duser.language=ko -Duser.region=KR -jar EasyTSP-2.8.0-RELEASE.jar
    * عربي ، java -Duser.language=zh -jar EasyTSP-2.8.0-RELEASE.jar
3. JDK版本使用1.8  
   JDK Version 1.8
4. 操作系统需安装图形化界面，否则无法正常运行  
   Operation System must contain Window System especially about Linux OS without "X Window System" installed. Otherwise it cannot run properly.  

###### 使用指南 Manual：
<video poster="http://139.155.13.244/poster.png" src="http://139.155.13.244/README.mp4" controls="controls" preload="auto" autoplay="autoplay">[如视频异常，请点击此处](http://139.155.13.244/README.html)
</video>

