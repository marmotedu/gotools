# Go 工具

下面这些列表可能会用到：

+ SpaceVim
+ Golang开发


## 安装

```bash
sudo yum -y install git-lfs    
git clone https://github.com/marmotedu/gotools
cd gotools    
git lfs install    
git lfs track *.tgz    
rm *.tgz    
git checkout -- .    
tar -xvzf gotools-for-spacevim.tgz -C $GOPATH/bin
```
