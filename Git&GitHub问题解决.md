



![image-20221011112356359](C:\Users\夏晓峰\AppData\Roaming\Typora\typora-user-images\image-20221011112356359.png)

![image-20221011112418004](C:\Users\夏晓峰\AppData\Roaming\Typora\typora-user-images\image-20221011112418004.png)





解决git下载报错：fatal: unable to access ‘https://github.com/…/.git/’:…

1、在git中执行git config --global --unset http.proxy和git config --global --unset https.proxy

git config --global --unset http.proxy
git config --global --unset https.proxy
2、在cmd下执行ipconfig/flushdns 清理DNS缓存

ipconfig/flushdns
3、重新执行git clone https://github.com/…/.git/’ 即可