# Notes for selfteaching

## Question lists
+ **Q1:** **如何在windows环境下，在Jupyter LAB的terminal里更改相关内容？**
  ***Answer:*** 光标直接移动到要改动的位置，双击即可开始编辑
+ **Q2:** **如何在windows环境下，在Jupyter LAB的terminal里用命令行向study branch做更新？**
  ***Answer：*** TBD  
    在Git Desktop里，左边栏下方有Commit to **xxx** (Branch name) button,在填写相应的summary和description之后，点击即可。
+ **Q3:** **如何在windows环境下，在Jupyter LAB里打开Git的Study Branch？**
  ***Answer：*** Jupyter lab不区分Branch，任何改动都会反映在Git Desktop中当前的Branch当中。  
+ **Q4:**  **没有搞懂为什么要用三个单引号？**
   >```age = int(input('''Please tell me your age: 
          an int number , e.g: 22
          '''))# 没有搞懂为什么要用三个单引号？
if age < 18:
    print('I can not sell you drinks...')
else:
    print('Have a nice drink!')```

+ **Q5** **怎么理解字符串的索引可以是负数？**


## 感受

+ 20190823: 今天在看（**注意真的是看，在电脑上看，更改代码的尝试不多**）1.E.5字符串和1.E.6容器这两节，（中间还曾经跳到1.E.7文件以及1.E.8处理前置引用这两节），看得痛苦无比，大脑在看这两章时是那种很凝滞不愿意动也带不动的感觉，勉勉强强看完字符串这张，后面的容器这节打算改天再看。相反，在看前置引用这一节时，就顺滑流畅很多。
 为什么会有这样的反差？可能的原因：
   1. 大脑习惯了形象的文字输入，对代码多抽象要求高的内容理解速度跟不上；
   2. 用错了不同类型知识的理解方法?那么编程知识属于哪种知识？应该不属于程序性知识
   >布卢姆对知识的分类方法，将知识分为事实性知识、概念性知识、程序性知识和元认知知识。
   ++ 事实性知识是指分离的、孤立的、“信息片段”形式的知识。学习事实性知识的关键，就是要背得快、记得牢，也就是记忆术要用得好。
   ++ 概念性知识是以结构化的形式组织起来的知识。它包含一些事实性知识，但这些事实性知识必须是相互联系、非任意性的、结构良好地组织起来的。概念性知识学习的关键，是要能自问自答出三个问题：
     +++ 自问1 这个知识的来龙去脉是什么
     +++ 自问2 这个知识与其他知识之间有什么联系
     +++ 自问3 这个知识有哪三个能用和不能用的场景
   如果学习抽象的概念性知识，在问这三个问题的基础上，再做到类比和比喻，学习效果就会更好。
   ++ 程序性知识是关于如何做某事的知识，通常以需要遵循的一系列步骤的形式出现。程序性知识的学习最容易陷入两个误区：低效率上手；无意识重复。但采用下面三个学习步骤，就能有效避免：
    +++ 步骤1 流程化：书面整理出程序性知识的流程
    +++ 步骤2 刻意用：有意识地应用流程步骤
    +++ 步骤3 一般化：提炼出更具一般性的流程

## Timeline
 + 201904xx 
    + install Anacoda on home laptop, no progress then
 + 20190812 
    + install Anacoda+Git desktop+Jupyter lab on work laptop
 + 20190813 
    + 1st commit to study branch; 
    + 1st merge to my master branch;
    + create 1st MD in my-notes folder;
    + Start to learn markdown
  