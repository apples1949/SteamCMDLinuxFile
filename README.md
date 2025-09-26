# SteamCMDLinuxFile
通过白嫖github下载更新好的steamcmd程序。需要的人自行参考以下指令下载，或者复刻仓库自己优化。针对steamcmd优化了压缩文件。如果steamcmd变更了文件结构说一声。  
常用指令:  
```
mkdir steamcmd
```
```
cd ./steamcmd
```
[gh-proxy加速源](https://gh-proxy.com/)：  
```
wget "https://gh-proxy.com/github.com/apples1949/SteamCmdLinuxFile/releases/download/steamcmd-latest/steamcmd_linux.tar.gz"
```
```
tar -xzf steamcmd_linux.tar.gz
```
```
./steamcmd.sh
```  
针对更新加速，单独对更新包package文件进行打包。解压在package文件夹中。记得删除旧文件  
[gh-proxy加速源](https://gh-proxy.com/)：  
```
wget "https://gh-proxy.com/github.com/apples1949/SteamCmdLinuxFile/releases/download/steamcmd-latest/package.tar.gz"
```
```
tar -xzf package.tar.gz
```
