# <center>machine learning</center>
## <center>chapter 1</center>
What is Machine Learning?
Arthur Samuel: the field  of study that gives computer the ability without being explicitly programmed
Tom Mitchell: A computer program is said to learn from experience E with respect to some class of tasks T and perfomance measure P,if its perfomance at tasks in T, as measured by P, improves with experience E.

key words in two definition:
1.  without being explicitly programmed
2. E for experience; T for tasks; P for perfomance measure; E for experience

我想要比较一下两种定义的异同：
1. 第一种定义显然类似于一种文科生的定义，基于模糊的不明晰的概念来做的一种定义，单从这一定义中看，我们很难看出有一种固定的方式来进行machine learning，不能重复之科学很难被称之为科学。
2. 第二种定义显然要科学的多，也现代的多，因为该定义可以数学化，E 和 T 是相关的，可以认为T是一个具有具体情境，以某种语言或存于人脑中的意识作为载体的有关于任务的描述，而E则是将T数学化的数据集如后面常出现的具有很多特征的很多个数的向量集（存在某种结构的可以反映T中全部输入输出信息的增删改查方式，可能是数据库数据结构相关？），T往往包括输入处理输出三个方面。P则是一个量化指标，如后面常出现的代价函数。 
<!--这里不知道说代价函数对不对，因为评价指标有很多，比如test case accuracy and cross validation accuracy F1 score and precision and recall; 可能是不对的，代价函数是程序实现过程中的手段，而不是最终评价算法的指标-->

给几个例子:
linear regression
E: input cases and relevant output
P: test cases accuracy

logistic regression

