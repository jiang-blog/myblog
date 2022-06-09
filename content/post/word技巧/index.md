---
title: 'Word写论文常用技巧'
date: 2021-12-09 14:02:26
tags: [折腾电脑,word]
draft: false
featured: false
isTop: false
---
# word技巧

## 章节编号



## 公式

### 公式编写

按`Alt + =`进入word公式编写，然后可以通过UnicodeMath进行代码编写，实际感觉和latex蛮相近，也可以通过公式栏改用Latex输入公式。

偶然发现已经有人做了更好的总结，感谢ArcSight的文章，比之后我的总结全面很多。

> [Word公式键入——UnicodeMath语法对照简表](https://blog.csdn.net/weixin_44224652/article/details/110673138)

~~这里引用[怎么在 Word 中方便地输入数学公式？](https://www.zhihu.com/question/24613226)中**赖枣**列出的常用输入，使用`?`表示空格键~~

#### 基础运算符

|  期望值   |   输入方式    |
| :-------: | :-----------: |
|  $\leq$   |  <= 或 \leq   |
|  $\geq$   |  >= 或 \geq   |
|   $\ll$   |   << 或 \ll   |
|   $\gg$   |   >> 或 \gg   |
| $\times$  |    \times     |
|  $\div$   |     \div      |
|  $\cdot$  |     \cdot     |
| $\cdots$  |    \cdots     |
| $\approx$ | ~~ 或 \approx |
|  $\neq$   |     \neq      |



#### 高级运算符

|     期望值     |   输入方式    |
| :------------: | :-----------: |
|   $\sqrt{a}$   |   \sqrt(a)?   |
| $\sqrt[b]{a}$  |  \sqrt(b&a)?  |
|     $a^b$      |     a^b?      |
|   $\partial$   |   \partial?   |
| $\int_{a}^{b}$ |   \int_a^b?   |
|   $\iint_A$    |    \iint_A    |
|   $\oint_C$    |    \oint_C    |
|   $\oiint_S$   |   \oiint_S    |
| $\sum_{i=1}^n$ | \sum_(i=1)^n? |

#### 上下标

|    期望值     | 输入方式  |
| :-----------: | :-------: |
|     $x^2$     |    x^2    |
|     $x_2$     |    x_2    |
| $x_{cc}^{bb}$ |  x_cc^bb  |
|   $\hat{x}$   |  x\hat??  |
|  $\tilde{x}$  | x\tilde?? |
|  $\check{x}$  | x\check?? |
|   $\dot{x}$   |  x\dot??  |
|   $\vec{x}$   |  x\vec??  |

#### 矩阵

|    期望值     | 输入方式  |
| :-----------: | :-------: |
| $(\matrix{1&2\\3&4})$ | (\matrix?(1&2@3&4)?)? |

#### 方程组

|                  期望值                   |       输入方式        |
| :---------------------------------------: | :-------------------: |
| $$\begin{cases}x=1\\y=2\\z=3\end{cases}$$ | (\matrix?(1&2@3&4)?)? |

在输入完一个部分后基本都需要**按至少一下空格进行转换**，其他常用符号也可通过将鼠标放置在公示栏中的符号上显示，或查阅 [官网pdf](http://www.unicode.org/notes/tn28/UTN28-PlainTextMath-v3.pdf)

![image-20211209162719875](https://cdn.jsdelivr.net/gh/jiang849725768/PrivateImgHost/img/202112091627754.png)

结束后可通过`文本`按钮转为文本，然后即可转换字体为times new roman字体，但如果存在编号统一转换会破坏编号居左的格式，只能分别转换，这个较为繁琐，还没找到好的解决办法

![文本](https://cdn.jsdelivr.net/gh/jiang849725768/PrivateImgHost/img/202112091616494.png)

### 公式编号

在公式后加上`#`号再输入公式编号，按下回车即可

可以使用题注方便地对公式进行编号，`引用`->`插入题注`，新建equation标签，修改题注格式为目标格式，然后勾选`从题注中排除标签`，即可插入公式编号，通过复制粘贴将其置于每个公式后，`ctrl+A`->`F9`进行域代码更新即可实现公式顺序编号。

PS：前提是合理地做好了章节编号

![image-20211212215248091](https://cdn.jsdelivr.net/gh/jiang849725768/PrivateImgHost/img/202112122153006.png)

### 公式引用



书签

## 感想

其实有时感觉部分步骤相比直接操作虽然自动化了，但前置动作太多，并没有减少足够的工作量，我想应该还有更好的方法去替代它们，希望以后能发现更多更好的方法。