# less
less/v3.8.1
google同源安全策略的关闭和开启

创建一个文件夹，用来保存关闭安全策略后的用户信息的:MyChromeDevUserData

关闭：
open -n /Applications/Google\ Chrome.app/ --args --disable-web-security  --user-data-dir=/Users/****/****/MyChromeDevUserData 
开启：
Chrome.app/ --args --enable-web-security  --user-data-dir=/Users/****/****/MyChromeDevUserData 