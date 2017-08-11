## 个人简介

* 姓 名：江先生
* 性 别：男
* 出生日期：1990.01.13
* 邮 箱：mrjlovetian@gmail.com

## 教育背景
毕业院校：郑州航空工业管理学院
专业：网络工程


## 相关经历
### 2014年7月就职北京亿高高尔夫iOS开发工程师
### 先后在公司创建不同私有控件，减轻重复工作，增加不同项目的组件化管理方式
### 在GitHub上也有自己对应的共有开源库，部分是自己用来做的demo，主要是控件式的分享！

## 练习

 这是什么东西（======）
 =========
 
 这个呢（---------）
 --------
 




## 标题 
### 哈哈 (###)
#### 哈哈哈 (####)
##### 嘿嘿 (#####)
###### 哦哦 (######)
####### 喵喵 (#######)
######## ad(########)


## 分类 
* red (*)

## 测试
- 消息 (-)
+ message (+)




## OL
<ol>
<li>段落1</li>
<li>段落2</li>
</ol>  （<ol><li>段落1</li><li>段落2</li></ol>）

<p>这样表示一个段落么？这是什么意思啊，搞不明白<p>（<p></p>）

## 代码区块 (<pre><code></code></pre>)
<pre><code> CGFloat normalRed, normalGreen, normalBlue, normalAlpha;
        CGFloat selectedRed, selectedGreen, selectedBlue, selectedAlpha;
        
        [self.itemTitleColor getRed:&normalRed green:&normalGreen blue:&normalBlue alpha:&normalAlpha];
        [self.itemTitleSelectedColor getRed:&selectedRed green:&selectedGreen blue:&selectedBlue alpha:&selectedAlpha];
        // 获取选中和未选中状态的颜色差值
        CGFloat redDiff = selectedRed - normalRed;
        CGFloat greenDiff = selectedGreen - normalGreen;
        CGFloat blueDiff = selectedBlue - normalBlue;
        CGFloat alphaDiff = selectedAlpha - normalAlpha;
        // 根据颜色值的差值和偏移量，设置tabItem的标题颜色
        leftItem.titleLabel.textColor = [UIColor colorWithRed:leftScale * redDiff + normalRed
                                                        green:leftScale * greenDiff + normalGreen
                                                         blue:leftScale * blueDiff + normalBlue
                                                        alpha:leftScale * alphaDiff + normalAlpha];
        rightItem.titleLabel.textColor = [UIColor colorWithRed:rightScale * redDiff + normalRed
                                                         green:rightScale * greenDiff + normalGreen
                                                          blue:rightScale * blueDiff + normalBlue
                                                         alpha:rightScale * alphaDiff + normalAlpha];</code></pre>

 

## 显示图片，添加个美女图片看看 (![Alt text]())
![Alt text](/girl.jpg)


