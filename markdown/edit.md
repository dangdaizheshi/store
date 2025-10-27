# Markdown 的基本语法

## 1、段落

我想从现在开始我会用它来格式化我的所有文档

## 2、字体设置

**加粗**
*斜体*
==高亮==
~~删除~~
<u>下划线</u>
<p style = "color: red; font-size: 20px">更改文本样式</p>

## 3、外链接

b站：[bilibili](https://www.bilibili.com/)

### 3.1、为链接添加标题

b站：[bilibili](https://www.bilibili.com/ "b站")

### 3.2、URL 和 电子邮件地址

<https://www.bilibili.com/>
<dangdaizheshi@qq.com>

## 4、插入图像

![picture]()

## 5、链接图像

[![picture]()](https://bilibili.com)

## 9、引用块

> 我是一个引用块

### 9.2、嵌套引用

> 我是一个引用块
> > 我是下一级
> > > 我是再下一级

### 9.3、带有其他元素的引用块

> #### Markdown 语法的学习
>
> - 什么是 Markdown ？
> - 为什么要用 Markdown ?
> - 支持 Markdown 的应用程序和组件，工具
> - Markdown 文件的工作原理
> - Markdown 的基本语法
>
> **真的真的** 是太好用了，我今天就开始**用起来 ！**

## 10、列表 - 有序列表

1. 第一项
2. 第二项
   1. 缩进的项目一
   2. 缩进的项目二
3. 第三项
4. 第四项
5. 第五项

## 11、列表 - 无序列表

- 第一项
- 第二项
  - 缩进项目一
  - 缩进项目二
    - 缩进缩进项目 1
    - 缩进缩进项目 2
  - 缩进项目三
- 第三项
- 第四项

## 12、分割线

***

## 13、表格

| 表头列 1 | 表头列 2 | 表头列 3 |
| :-------- | :--------: | --------: |
| 数据 1   | 数据 2   | 数据 3   |
| 数据 4   | 数据 5   | 数据 6   |

### 2.3、复杂表格（需要合并单元格）

<table border="1" width="800">
    <thead>
        <tr>
            <th colspan="2">需求：V0.3版本规划</th>
            <th>优先级</th>
            <th>任务分解</th>
            <th>产品负责人</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="3">功能模块1</td>
            <td>具体事项1</td>
            <td>3</td>
            <td>任务1</td>
            <td rowspan="3">@翠花</td>
        </tr>
        <tr>
            <td rowspan="2">具体事项2</td>
            <td>4</td>
            <td>任务2</td>
        </tr>
        <tr>
            <td>1</td>
            <td>任务3</td>
        </tr>
        <tr>
            <td rowspan="6">功能模块2</td>
            <td>具体事项1</td>
            <td>2</td>
            <td>任务1</td>
            <td rowspan="6">@美美</td>
        </tr>
        <tr>
            <td rowspan="4">具体事项2</td>
            <td>3</td>
            <td>任务1</td>
        </tr>
        <tr>
            <td>2</td>
            <td>任务2</td>
        </tr>
        <tr>
            <td>1</td>
            <td>任务3</td>
        </tr>
        <tr>
            <td>4</td>
            <td>任务4</td>
        </tr>
        <tr>
            <td>具体事项3</td>
            <td>1</td>
            <td>任务1</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <th colspan="5">备注信息</th>
        </tr>
        <tr>
            <td colspan="5">...</td>
        </tr>
    </tfoot>
</table>

## 14、脚注