#### 安装package control组件:
1. 按Ctrl+`调出console（注：安装有QQ输入法的这个快捷键会有冲突的，输入法属性设置-输入法管理-取消热键切换至QQ拼音）
2. 粘贴一下代码回车
```
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())

```

#### ubunt系统下输入中文
参考附件a.html

哈哈
s是非得失
LD_PRELOAD=$SUBLIMT_TEXT_3_HOME/libsublime-imfix.so $SUBLIMT_TEXT_3_HOME/sublime_text