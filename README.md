# 字体蜘蛛

按需提取字体，并生成压缩文件。


## 项目结构

```bash
|-- _font                         # inqiu.com所有字体文件备份，可以忽略
|-- css                           # css样式
|-- font                          # 字体文件
|   |-- .font-spider              # 自动生成目录，css所使用字体备份
|-- html                          # html
|   |-- index.html                # html文件，可以随意新增*.html
|-- node_modules				  # 运行依赖
|-- package.json                  # 运行配置
|-- README.md                     # 项目说明
```


## 使用

```bash

# 克隆项目
git clone https://github.com/eyeliving/font-spider.git

# 安装依赖
npm install

# 生成字体文件【生成的字体在font文件夹下，此文件夹下的.font-spider为备份】
npm run go

```
