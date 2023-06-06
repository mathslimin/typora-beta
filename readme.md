# Readme

Typora開始收費了，我真的嚇到吃手手了。

備份一下最後的Beta測試版 v0.11.18。

[下載 (Windows x64)](https://github.com/HowardWhile/typora-beta/raw/main/typora-update-x64-1117.exe)

[下載 (Windows x86)](https://github.com/HowardWhile/typora-beta/raw/main/typora-update-ia32-1117.exe)

[下載 (Linux x64)](https://github.com/HowardWhile/typora-beta/raw/main/typora_0.11.18_amd64.deb)

[下載 (Mac)](https://github.com/HowardWhile/typora-beta/raw/main/Typora-0.11.18.dmg)

## 值得紀念的最後的開發版本release

#### 0.11.18

1. Add warnings when user try to edit file from backup location.

2. Line break should be rendered as whitespace when ignore line break is enabled.

3. Fix new file in tile tree will result to duplicate files.

4. Fix bug that table with tabs cannot be correct parsed.

5. Fix inline math preview issue.

6. Fix bug that users cannot jump from some internal links.

7. Fix some cursor issue.

8. Fix Greek language spellcheck on older Windows and Linux.

[Download (Windows x64)](https://download.typora.io/windows/typora-update-x64-1117.exe) [Download (Windows x86)](https://download.typora.io/windows/typora-update-ia32-1117.exe) [Download (Linux x64)](https://download.typora.io/linux/typora_0.11.18_amd64.deb)



> https://typora.io/dev_release.html

解决typora提示This beta version of Typora is expired, please download and install a newer version
https://www.zhaojun.ink/archives/typora-newer-version

上面提示的大概意思是beta版本的typora已经过期了，需要下载最新版本，但是现在正式版的typora是需要收费的。遂在网上寻找解决办法，在此记录一下。

通过修改注册表，可以解决这个问题

win+r 打开运行窗口
在搜索栏输入regedit，回车后打开注册表
在注册表中找到：计算机\HKEY_CURRENT_USER\Software\Typora
鼠标右键Typora，选择权限
选择Administraors，将下面的权限选择为拒绝
完全控制，读取
重新打开Typora，发现可以正常运行了
