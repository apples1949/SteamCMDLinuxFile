# SteamCMDLinuxFile
通过白嫖github下载更新好的steamcmd程序。需要的人自行参考以下指令下载，或者复刻仓库自己优化。针对steamcmd优化了压缩文件。如果steamcmd变更了文件结构说一声。下载链接最好是获取第三方加速链接 https://github.com/xiaoxuan6/github-mirror 或者通过更改UA下载gitee加速源 保不齐哪天寄了  
常用指令:  
```
mkdir steamcmd
```
```
cd ./steamcmd
```
```
wget https://raw.kkgithub.com/apples1949/SteamCMDLinuxFile/main/build/steamcmd_linux.tar.gz
```
Gitee加速源：  
```
wget -U "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.212 Safari/537.36" "https://gitee.com/apples1949/SteamCMDLinuxFile/raw/main/build/steamcmd_linux.tar.gz"
```
```
tar -xzf steamcmd_linux.tar.gz
```
```
./steamcmd.sh
```  
针对更新加速，单独对更新包package文件进行打包。解压在package文件夹中。记得删除旧文件  
常用指令：  
```
wget https://raw.kkgithub.com/apples1949/SteamCMDLinuxFile/main/build/package.tar.gz
```
Gitee加速源：  
```
wget -U "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.212 Safari/537.36" "https://gitee.com/apples1949/SteamCMDLinuxFile/raw/main/build/package.tar.gz"
```
```
tar -xzf package.tar.gz
```
