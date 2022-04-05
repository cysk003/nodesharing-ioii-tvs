# githubhosts

#### 如何操作操作系统的 hosts 文件

Windows 下在：

`C:/Windows/system32/drivers/etc/hosts`

苹果 Mac OSX 和 Ubuntu 等linux系一般在： 

`/etc/hosts`
 

#### hosts 文件内关于 github IP 地址的内容



```
199.232.69.194 github.global.ssl.fastly.net
140.82.112.4 www.github.com
185.199.108.153 assets-cdn.github.com
185.199.109.153 assets-cdn.github.com
185.199.110.153 assets-cdn.github.com
185.199.111.153 assets-cdn.github.com
185.199.108.153 documentcloud.github.com
185.199.109.153 documentcloud.github.com
185.199.110.153 documentcloud.github.com
185.199.111.153 documentcloud.github.com
140.82.114.3 gist.github.com
185.199.108.153 help.github.com
185.199.109.153 help.github.com
185.199.110.153 help.github.com
185.199.111.153 help.github.com
140.82.112.9 nodeload.github.com
199.232.68.133 raw.github.com
140.82.112.18 status.github.com
140.82.113.18 training.github.com
199.232.68.133 raw.githubusercontent.com
199.232.68.133 user-images.githubusercontent.com
199.232.68.133 avatars1.githubusercontent.com
199.232.68.133 avatars2.githubusercontent.com
199.232.68.133 avatars3.githubusercontent.com
199.232.68.133 cloud.githubusercontent.com
140.82.113.6 api.github.com
```



#### 改完如何刷新生效
 

**Windows** 
```
ipconfig /flushdns
```

**Ubuntu** 
```
sudo systemctl restart nscd
```

**Mac** 
```
sudo killall -HUP mDNSResponder
```

