# 我的 Sildes

自己做的小工具, 可以直接把 markdown 文件转换成 revealjs 的 ppt 文件.

参照 [「teddy-ma」的 sliders](https://github.com/teddy-ma/sliders)，稍微做了一些优化。

## 使用方式

### 克隆项目(可以 fork 到自己的仓库)

    git clone https://github.com/mjd507/Sildes.git
    cd Sildes

### 安装依赖(确保 node 环境已安装)

    npm install

### 编辑 slider

在 `src` 目录下新建 `xxx.md` 文件, 然后执行

    npm run build

来生成 html. 或者使用命令

    npm run watch

就可以实时进行修改

### 预览

    npm run preview

然后访问 <http://localhost:8000/>

### 清理构建

    npm run clean
