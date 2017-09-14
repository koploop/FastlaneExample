fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

## Choose your installation method:

<table width="100%" >
<tr>
<th width="33%"><a href="http://brew.sh">Homebrew</a></td>
<th width="33%">Installer Script</td>
<th width="33%">Rubygems</td>
</tr>
<tr>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS or Linux with Ruby 2.0.0 or above</td>
</tr>
<tr>
<td width="33%"><code>brew cask install fastlane</code></td>
<td width="33%"><a href="https://download.fastlane.tools">Download the zip file</a>. Then double click on the <code>install</code> script (or run it in a terminal window).</td>
<td width="33%"><code>sudo gem install fastlane -NV</code></td>
</tr>
</table>

# Available Actions
## iOS
### ios xks_build
```
fastlane ios xks_build
```
通用构建入口

执行命令: bundle exec fastlane xks_build type:dev 或 fastlane xks_build type:dev
### ios xks_step
```
fastlane ios xks_step
```
正式开始打包动作
### ios xks_cocoapods
```
fastlane ios xks_cocoapods
```
执行cocoapods操作
### ios xks_ftp
```
fastlane ios xks_ftp
```
上传FTP
### ios xks_mail
```
fastlane ios xks_mail
```
发送邮件
### ios xks_test
```
fastlane ios xks_test
```
执行测试

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
