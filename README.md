# Unity2020-Crack
unity hub会先启动
不查不知道，unity公司好无耻
{"net":{"http_server_properties":{"servers":[{"https://vars.hotjar.com":{"supports_spdy":true}},{"https://www.linkedin.com":{"supports_spdy":true}},{"https://px.ads.linkedin.com":{"supports_spdy":true}},{"https://script.hotjar.com":{"supports_spdy":true}},{"https://vc.hotjar.io":{"supports_spdy":true}},{"https://p.adsymptotic.com":{"supports_spdy":true}},{"https://connect-prd-cdn.unity.com":{"supports_spdy":true}},{"https://unity3d.com":{"supports_spdy":true}},{"https://api.unity.cn":{"supports_spdy":true}},{"https://connect.unity.com":{"supports_spdy":true}},{"https://fonts.googleapis.com":{"supports_spdy":true}},{"https://fonts.gstatic.com":{"supports_spdy":true}},{"https://www.googletagmanager.com":{"supports_spdy":true}},{"https://zz.bdstatic.com":{"supports_spdy":true}},{"https://connect-cdn-public-prd.unitychina.cn":{"supports_spdy":true}},{"https://www.googleadservices.com":{"supports_spdy":true}},{"https://www.google-analytics.com":{"supports_spdy":true}},{"https://connect-cdn-china.unitychina.cn":{"supports_spdy":true}},{"https://googleads.g.doubleclick.net":{"supports_spdy":true}},{"https://bid.g.doubleclick.net":{"supports_spdy":true}},{"https://stats.g.doubleclick.net":{"supports_spdy":true}},{"https://static.hotjar.com":{"supports_spdy":true}}],"version":5},"network_qualities":{}}
这些都是广告公司的链接吧，untiy时刻访问这些链接用来判断连接状况，属于间谍软件，川普赶紧查它

Unity公司真好笑，弄了个hub启动editor，2.3以前的版本真的好容易就。。。。。


npm install -g asar
2.打开UnityHub安装目录如 C:\Program Files\Unity Hub\resources。
3.在C:\Program Files\Unity Hub\resources打开命令行,执行以下命令解压app.asar。
C:\Program Files\Unity Hub\resources> asar extract .\app.asar app
解压后删除C:\Program Files\Unity Hub\resources\app.asar。
4.修改C:\Program Files\Unity Hub\resources\app\src\services\licenseService\licenseClient.js
getLicenseInfo(callback) {
    // load license
    // get latest data from licenseCore
    //licenseInfo.activated = licenseCore.getLicenseToken().length > 0;//注释这行
    licenseInfo.activated = true;//新增这行
    licenseInfo.flow = licenseCore.getLicenseKind();
5.C:\Program Files\Unity Hub\resources\app\src\services\licenseService\licenseCore.js
verifyLicenseData(xml) {
    return new Promise((resolve, reject) => {
        resolve(true);//新增这行
      if (xml === '') {
      
  unity hub到了2.3以后学聪明啦，写了个c++的license.lib，里面有个函数，跟上面脚本的一样用吧
  imp__register_license_，赶紧加班更新新版本啦
  
  
  哈哈哈哈哈哈哈
