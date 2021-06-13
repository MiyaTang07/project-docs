### maxOS-Chorme浏览器跨域设置（注意全半角输入法）
```
open -a "/Applications/Google Chrome.app" --args --disable-web-security  --user-data-dir=/Users/yourname/chromeDevUserData/

```

### 打开本地.bash_profile文件
```
vim ~/.bash_profile
```


### 全局设置该指令别名--ky

```
alias ky='open -a /Applications/Google\ Chrome.app --args --disable-web-security --user-data-dir=/Users/tangjiao/chromeDevUserData/'
```

### 更新.bash_profile文件
```
source ~/.bash_profile
```

### 注意事项
- 控制台使用ky指令打开跨域浏览器时，需要关闭之前打开的Chrome浏览器窗口！