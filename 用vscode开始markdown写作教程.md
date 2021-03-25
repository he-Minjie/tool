
## 1. 下载和安装vscode
### 1.1 下载
[vscode官网](https://code.visualstudio.com/)   
![安装注意](https://raw.githubusercontent.com/he-Minjie/myImages/myImages/images/%E5%AE%89%E8%A3%85%E6%B3%A8%E6%84%8F.png)  
安装中文包：点击左侧工具栏的扩展(Ctrl+Shift+X),输入Chinese，点击Install安装  
配置环境：快捷键[Ctrl+Shift+P]调出查找命令栏，输入language，找到Configure Display Language，点击，选择locale属性为“zh-CN”  
重启vscode，安装成功，配置好啦。
### 1.2 国内下载vscode速度慢解决办法
万物皆可镜像！！！
在官网找到需要下载的文件，点击下载，有这么个地址，复制下来  
![vscode下载镜像](https://raw.githubusercontent.com/he-Minjie/myImages/myImages/images/vscode%E4%B8%8B%E8%BD%BD%E9%95%9C%E5%83%8F.png)  
复制后粘贴到任意浏览器下载，这就是国内的镜像。
麻麻再也不用担心我下载速度慢啦！  
### 1.3 安装Markdown增强插件
直接用不给力，需要下载一些插件
+ Markdown All in One  
  是一个组合包，把最常用的Markdown都给你装好
+ Markdown Preview Github Styling  
  是Github使用的Markdown渲染样式，很简洁。使用这个样式，在本地就能预览Markdown文件最终在Github Pages中显示的效果。
+ Markdown PDF   
  可将MD格式的文件输出为pdf格式
### 1.4 那就立马开始写第一篇Markdown文档吧！
为了集中管理Markdown文档，在固定的地方专门建一个文件夹。使用vscode打开这个文件夹，会在左侧的高航窗口看到以下显示：
![打开文件夹](https://raw.githubusercontent.com/he-Minjie/myImages/myImages/images/%E6%89%93%E5%BC%80%E6%96%87%E4%BB%B6%E5%A4%B9.png)
在这个目录下，可以新建文档，注意文档名一定要带 **.md**的后缀。  
当输入 **.md** 的后缀时，新建的文件名前面多了一个蓝色向下的箭头logo，这代表它已经被vscode识别为markdown文件了。  
现在，就可以开始写啦！  
在开始之前，请点击右上角的这个图标：  
![两栏图标](https://raw.githubusercontent.com/he-Minjie/myImages/myImages/images/%E4%B8%A4%E6%A0%8F%E5%9B%BE%E6%A0%87.png)  
页面就会变成两栏分列的样子，右侧就是markdown文件被渲染为HTML的预览；  
由于我们安装了Github的渲染风格，这里会安装Github的样式渲染markdown文件。
## 2. MarkDown基本语法
### 2.1 标题
`#` 一级标题        
`##` 二级标题  
`###` 三级标题  
`####` 四级标题  
`#####` 五级标题  
`######` 最多支持六级标题  
# 一级标题      
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 最多支持六级标题
### 2.2 段落
换行有两种方法，在一行文字结尾加“两个空格”，直接空一行(但间距过大)  
### 2.3 正文
`*`斜体字`*`  `_`斜体字`_`  
`**`粗体`**`  `__`粗体`__`  
`***`斜粗体字`***`  `___`斜粗体字`___`    
*斜体字* _斜体字_  
**粗体** __粗体__  
***斜粗体字*** ___斜粗体字___  
### 2.4 分割、删除、下划线
`---`  `***`

***  
`~~`删除线`~~`  （左右两个~）  
~~删除线~~  
`<u>`下划线`</u>`  
<u>下划线</u>  
另外说明MD也可以使用HTML语法编写  

### 2.5 无序列表、有序列表
无序列表采用“+/-/*加空格”

`+` 第一个  
`+` 第二个  
`-` 第一个  
`-` 第二个  
`*` 第一个  
`*` 第二个  
+ 第一个  
+ 第二个
- 第一个
- 第二个
* 第一个
* 第二个  

有序列表词用“数字加.加空格”，同时有序列表中可以用“TAB键加无序子列表”  
`1.` 第一个  
`2.` 第二个  
    `-` 小一  
    `-` 小二  
`3.` 第三个  
1. 第一个
2. 第二个
    - 小一
    - 小二
3. 第三个
### 2.6 区块
用大于号>，要几层嵌套就打几个，但同级嵌套嵌套要换行，行末尾要加两个空格  
`>1`  
`>>1.1`  
`>>>1.1.1`   
`>>>1.1.2`    
>1  
>>1.1  
>>>1.1.1  
>>>1.1.2  
### 2.7 代码
左右两边加倒引号" ` "   

`printf();`   
左右两边三个倒引号 " ``` " 包住代码,且在起始倒引号后加编程语言类型可以使语法高亮
```c
int a=1;
int b=2;
int c;
c=a+b;
```
### 2.8 链接
用方括号包住链接名字，在英文圆括号内填入网址  
`[`我的gishub主页`](`https://github.com/he-Minjie`)`  
[我的gishub主页](https://github.com/he-Minjie)  
也可直接用小于号<，大于号>包住链接  
`<`https://github.com/he-Minjie`>`  
<https://github.com/he-Minjie>
### 2.9 图片
用叹号！加方括号内写图片名和英文圆括号内写图片链接的形式
MD文档本身不能存图片，图片链接可以使用本地地址，或者图床外链  
`![`cat`](`https://raw.githubusercontent.com/he-Minjie/myImages/myImages/images/cat.jpg`)`    
![cat](https://raw.githubusercontent.com/he-Minjie/myImages/myImages/images/cat.jpg)
### 2.10 表格
用制表符生成第一行是所有的列，第二行是减号填充，第三行才是内容，在第二行的减号左侧加英文冒号是左对齐，右侧加是右对齐，两边都加是居中对齐   
`|`列1        `|`列2        `|`列3         `|`  
`|:`----------`|`----------`:|:`----------`:|`  
`|`内容`|`内容`|`内容`|`  
`|`这个内容很长很长`|`这个内容很长很长`|`这个内容很长很长`|` 

|列1        |列2        |列3         |
|:----------|----------:|:----------:|
|内容|内容|内容|
|这个内容很长很长|这个内容很长很长|这个内容很长很长| 
### 2.11 Front-matter
对于使用markdown写博客的人来说必不可少，它是文章的信息头，在渲染文中不会显示(都是符号加冒号加空格)

---
title: 标题  
date: 2021/03/21 20:59:00  
update: 2021/03/21 20:59:00  
categories: 
- 分类一
- 分类二  
tages:
- 标签一
- 标签二
---    
## 3. 小结
- 本文主要介绍了markdown 编辑器 vscode 的安装流程  
- vscode官网下载慢，如何解决——用镜像下载
- markdown 基本语法
- 那就开始写你的第一篇 markdown 文档吧，现在就开始吧！  

最后，推荐几个学习教程：
- [使用vscode开始Markdown写作之旅](https://zhuanlan.zhihu.com/p/56943330) 
- [国内下载vscode速度慢问题解决](https://zhuanlan.zhihu.com/p/112215618)
- [markdown 编辑文章](https://b23.tv/mIc2ZJ)