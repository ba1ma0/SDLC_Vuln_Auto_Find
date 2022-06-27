# SDLC_Vuln_Auto_Find SDCL安全测试人员能力沉淀
# 文章
https://www.freebuf.com/articles/web/337354.html

# 使用
## 第一步 加载配置文件
Burpsuite->Project->Project Options-> Load project options

![](https://raw.githubusercontent.com/ba1ma0/SDLC_Vuln_Auto_Find/main/1.png)

## 第二步 配置配置文件
Burpsuite->Proxy->Options->Match and Replace
### SSRF自动检测
在方框中打上对号并将“https://SSRFByHttpFile.sjdjsjdjjsdjjsd.ceye.io” 替换为你自己的dnslog地址
![](https://raw.githubusercontent.com/ba1ma0/SDLC_Vuln_Auto_Find/main/2.png)
### XSS
在你需要自动检测的点打上对号
![](https://raw.githubusercontent.com/ba1ma0/SDLC_Vuln_Auto_Find/main/3.png)

上面只是举了两个例子,实际规则中有很多检测漏洞,你可以根据自己的实际情况选择是否进行自动检测
## 第三步 自定义扩展插件
根据文章中的介绍,你可以自己扩展规则处理自己的场景

# 有疑问🤔️联系作者
vx: 5ed0c42e63c9c2145990351ccaec4da5
