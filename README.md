﻿## MR-Puzzles

> - 1: 一个人只能提交一次，相同的MR只记录最先提交的，另外，总提交数统计可能也会出错...所以发现有问题的请在提交截止前单独发非提交邮件指出
> - 2: 发现别人的MR有误或者题目有问题可以[发邮件给mrhuntor@sina.com](mailto:mrhuntor@sina.com)指出, 降低别人的得分==提高自己的得分=D
> - 3: 希望各位提交的时候能把MR整理成txt文件,然后用学号命名,已经提交的同学不用再次提交=D
> - 4: 特别提醒: MR跟问题本身性质还是有区别的, 请大家在想MR的之前先看一下[什么样的mr才是合格的mr](#什么样的mr才是合格的mr)的小标题=]

---

**提交汇总**

| 学号 | 有效提交数 | 总提交数 | 提交时间 |
| --- | ----- | --- | --- |
| 131220101 | 0 | 8 | 2016/6/9 15:59 |


---

[MR-Puzzles目录](#mr-puzzles)

[TOC]

- [举个栗子:](#举个栗子)

- [题目列表:](#题目列表)

	- [题目名称: 1 # Binary Search on Sorted Array [有序数组的二分查找]](#题目名称-1binary-search-on-sorted-array有序数组的二分查找)
	- [题目名称: 2 # k-th Occurrence of x in Unsorted Array [x在无序数组中的第k次出现]](#题目名称-2k-th-occurrence-of-x-in-unsorted-arrayx在无序数组中的第k次出现)
	- [题目名称: 3 # Shortest Path in an Undirected Graph[无向图的最短路]](#题目名称-3Shortest-Path-in-an-Undirected-Graph无向图的最短路)
	- [题目名称: 4 # Solving a System of Linear Equations with Gaussian Elim [用高斯消去法解方程]](#题目名称-4solving-a-system-of-linear-equations-by-gaussian-elim用高斯消去法解方程)
	- [题目名称: 5 # standard deviation[计算标准差]](题目名称-5standard-deviation计算标准差)
	- [题目名称: 6 # Naive Bayes [平凡贝叶斯]](#题目名称-6naivebayes平凡贝叶斯)
	- [题目名称: 17 # Matrix Transpose [矩阵转置]](#题目名称-17matrix-transpose矩阵转置)
	- [题目名称: 18 # Maxsum [连续子数组的最大和]](#题目名称-18max-sum连续子数组的最大和)
	- [题目名称: 19 # String Reverse [字符串反转]](#题目名称-19string-reverse字符串反转)
	- [题目名称: 20 # Binary Search Tree [二叉搜索树]](#题目名称-20binary-search-tree二叉搜索树)
	- [题目名称: 21 # Minimal spanning Tree [最小生成树]](#题目名称-21minimal-spanning-tree最小生成树)
	- [题目名称: 23 # Euler Circle [欧拉回路]](#题目名称-23euler-circle欧拉回路)
	- [题目名称: 25 # Connected Graph [连通图]](#题目名称-25connected-graph连通图)
	- [题目名称: 26 # Words Replacement [单词替换]](#题目名称-26words-replacement单词替换)
	- [题目名称: 27 # Candy Eating [吃糖果问题]](#题目名称-27candy-eating吃糖果问题)
	- [题目名称: 33 # Plalindrome [最长回文子序列]](#题目名称-33plalindrome最长回文子序列)
	- [题目名称: 35 # Inverse Number [逆序对]](#题目名称-35inverse-number逆序对)
	- [题目名称: 39 # Merge [数组合并]](#题目名称-39merge数组合并)
	- [题目名称: 44 # Max Matching of Bigraph [二部图的最大匹配]](#题目名称-44max-matching-of-bigraph二部图的最大匹配)
	- [题目名称: 46 # Max Vertex Independent Set [最大点独立集]](#题目名称-46max-vertex-independent-set最大点独立集)
	- [题目名称: 47 # Domination Set [支配集]](#题目名称-47domination-set支配集)
	- [题目名称: 48 # Vertex Covering Set [点覆盖集]](#题目名称-48vertex-covering-set点覆盖集)
	- [题目名称: 49 # Edge Coloring [边染色]](#题目名称-49edge-coloring边染色)
	- [题目名称: 50 # Vertex Coloring [点染色]](#题目名称-50vertex-coloring点染色)
	- [题目名称: 51 # Max Clique [最大团]](#题目名称-51max-clique最大团)
	- [题目名称: 52 # Planar Graph [可平面图]](#题目名称-52planar-graph可平面图)
	- [题目名称: 53 # Reverse Arc [反向弧]](#题目名称-53reverse-arc反向弧)
	- [题目名称: 56 # Directed Tree [有向树]](#题目名称-56directed-tree有向树)
	- [题目名称: 57 # Euler Digraph [Euler有向图]](#题目名称-57euler-digrapheuler有向图)
	- [题目名称: 58 # Nameking of Tournament [竞赛图中的王]](#题目名称-58nameking-of-tournament竞赛图中的王)
	- [题目名称: 59 # Root Tree [根树]](#题目名称-59root-tree根树)
	- [题目名称: 61 # Precode of Binary Tree [二叉树的二元前缀码]](#题目名称-61precode-of-binary-tree二叉树的二元前缀码)
	- [题目名称: 62 # Huffman [Huffman算法求最优二叉树]](#题目名称-62huffmanhuffman算法求最优二叉树)
	- [题目名称: 63 # Ford-fulkerson [最大流问题的ford-fulkerson算法]](#题目名称-63ford-fulkerson最大流问题的ford-fulkerson算法)
	- [题目名称: 66 # Heap Building [建堆]](#题目名称-66heap-building建堆)
	- [题目名称: 68 # Red-black Tree [红黑树]](#题目名称-68red-black-tree红黑树)
	- [题目名称: 70 # B-tree [B树]](#题目名称-70b-treeb树)
	- [题目名称: 72 # Number of Prime [素数个数]](#题目名称-72number-of-prime素数个数)
	- [题目名称: 74 # Line Segment Intersection [线段相交]](#题目名称-74line-segment-intersection线段相交)
	- [题目名称: 77 # Stack Game [栈]](#题目名称-77stack-game栈)
	- [题目名称: 82 # Hex Convert [进制转换]](#题目名称-82hex-convert进制转换)


---

### 举个栗子:

---

#### **题目名称:** 1#sin[正弦]
**题目描述:**

	计算输入浮点数的正弦值.

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `x` | `double` | 输入的浮点数 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `double` | 正弦计算结果 |

**样例MR:**

> -  当输入加π时, 输出取反

---

### **什么样的MR才是合格的MR**
- 能反映2对(或多对)输入输出间关系
	- 反例1: *把同一个输入运行两遍, 结果相同*

- 根据MR能生成无穷多对输入输出对
	- 反例3: *当第1个输入等于-1, 第2个输入等于1时, 两个输出相加等于0*

- 不要万能MR
	- 反例4: 对于图相关的程序: *改变图点/边的输入顺序, 输出不变*

- 直接在输入的时候被过滤的MR
	- 反例7: *输入 G 输出 y, 在 G 上 V 点增加一条自己连接自己的边, 输出不变.* [23](#题目名称-23euler-circle欧拉回路)

- 不一定正确的MR
	- 反例8: *输入 s0, s1, s2 逆序, 输出为 d 逆序.* [26](#题目名称-26words-replacement单词替换)

- 不完整的MR
	- 反例9: *输入 (A, n, x)， 输出 y; 1. 若 y != -1 && y != n-1，将 (A[y+1:n], n-y-1, x') 作为新的输入，其中x' < x, 输出 y' == -1. * [1](#题目名称-1binary-search-on-sorted-array有序数组的二分查找)

- 非常奇怪的MR
	- 反例20: *取出G中的结点，添加边使得G'连通且存在欧拉回路。 将G'中的边添加到G中（两结点间可能会有多条边），得到G'', G 和 G''的输出结果相同* [23](#题目名称-23euler-circle欧拉回路)

- 不精确的MR
	- 反例32: *输入原图G，得结果y。G中任意去掉一个边，再次输入，得新结果y'。y为true的话，y'只能为true。y为false的话，y'可能为false或true。同理，任意添加一个边，y为true的话，y'可能为false或true。y为false的话，y'只能为false。* [52](#题目名称-52planar-graph可平面图)

---


### **题目列表**

---

#### **题目名称:** 1#Binary Search on Sorted Array[有序数组的二分查找]
**题目描述:**

	有序不重复数组的二分查找.

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A` | `int[]` | 被查找的有序整数数 |
| `n` | `int` | A的长度 |
| `x` | `int` | 查找的目标 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `int` | `-1`代表没有找到, 否则为下标|

**样例MR:**


> -  输入 A1 (递增), 查找 x1, 输出 y1; A2 为 A1 每个数乘 ­‐1 (递增), 查找 -x1, 输出 y2. A1 长度为 n. 若 y1 == ­‐1, 则 y2 == ‐1; 若 y1 != ­‐1, 则 y1 + y2 == n ­‐ 1 (下标从 0 开始)
> -  对于输入（A, n, x），输出为y，那么将A中所有数都乘以2，得到A’，则输入（A’, n, 2x）的输出仍为y。
> -  输入(A,n,x),输出y;令A1=A[0,floor(n/2)-1];A2=A[floor(n/2),n-1];输入(A1,floor(n/2),x)输出a;输入(A2,n-floor(n/2),x)输出b;如果a=-1且b!=-1,则y=floor(n/2)+b;如果a!=-1且b=-1,则y=a;如果a=-1且b=-1,则y=-1;
> -  输入(A,n,x)(递增)输出y;数组A1[2n]满足:如果-1<i<n,A1[i]=A[i],否则A1[i]=A1[i]+abs(A[n-1]);输入(A1,2n,x+abs(A[n-1]))输出y1,如果y=-1,y1=-1;否则y1=y+n
> -  对于输入(A, n, x),输出为y,那么对于输入(A, n, x+1)输出为y2，如果y2等于-1，那么y2<=y1(包含y1=-1的情况),如果y2不等于-1，那么y2>y1(包含y1=-1的情况)
> -  假设输入（A, n, x), 输出y;令数组B={A，max(max(A), x)+1}, 输入(B, n+1, x), 仍输出y.

---

#### **题目名称:** 2#k-th Occurrence of x in Unsorted Array[x在无序数组中的第k次出现]
**题目描述:**

	求x在无序数组中第k次出现的下标

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A` | `int[]` | 被查找的无序整数组 |
| `n` | `int` | 数组长度 |
| `x` | `int` | 查找的目标 |
| `k` | `int` | 第几次出现 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `int` | `-1`代表没有找到, 否则为下标 |

**样例MR:**

> -  如果输入(A, x, k), 输出y等于-1, 则输入(A, x, k+1), 输出也等于-1;
	如果输入(A, x, k), 输出y不等于-1, 则输入(A, x, k+1), 输出等于-1或者输出大于y.
> -  对于输入（A, x, k），输出为y，那么将A中所有数都乘以2，得到A’，则输入（A’, 2x, k）的输出仍为y。
> -  分别输入 （A，x，1），（A，x，2）...（A，x，n），n为A长度；则结果y1 到 yn 先保持正数升序，直到一个数为-1，后面所有均为-1

---

#### **题目名称:** 3#Shortest Path in an Undirected Graph[无向图的最短路]
**题目描述:**

	求无向图的最短路

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `无向图` | 所需要求最短路的无向图，保证连通 |
| `a` | `int` | 起点 |
| `b` | `int` | 终点 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `P` | `int[]` | 从a到b的最短路的路径 |
| `length` | int | 从a到b的最短路的路径长度 |

**样例MR:**

---

#### **题目名称:** 4#Solving a System of Linear Equations by Gaussian Elim[用高斯消去法解方程]
**题目描述:**

	使用高斯消去法解多元一次方程组, 保证只有1个解

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A` | `double[][]` | 系数N*M矩阵 |
| `b` | `double[]` | 等号右边的常数向量 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `x` | `double[]` | 计算得出的解向量 |

**样例MR:**

> -  当A里的每一个数都乘以2, b里的每一个数都乘以2时, 输出不变
> -  将矩阵A的列向量，第m列与第n列进行互换，输出结果中的第m分量与第n分量互换
> -  矩阵A的第m行和n行互换位置，b里第m行和n行也互换，则结果不变
> -  将A中的第k列乘以2，得到的解向量中的第k个分量为x第k个分量的1/2
> -  输入 A b1， 输出 x1； 输入 A b2， 输出 x2； 输入 A （b1 + b2）（对应元素相加）， 输出 （x1 + x2）（对应元素相加）
> -  输入(A,b)输出x,输入(A的逆,b)输出y,则(A^2)x=y
> -  输入(A,b)输出x,输入((A*)的逆,b)输出y,则|A|x=y
> -  A中的第m行的各元素，分别对应减去第n行的各元素值*k，B中m行值减去n行的值*k。（k不为0）将新的A、B输入，所得结果不变。
> -  假设输入（A, b），输出y1,输入(A,b/k)(k>0),输出y2,则y2=y1/k;

---

#### **题目名称:** 5#standard deviation[计算标准差]
**题目描述:**

	计算输入数组的标准差

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A` | double[] | double数组 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `S` | `double` | A的标准差 |

**样例MR:**

---

#### **题目名称:** 6#NaiveBayes[平凡贝叶斯]
**题目描述:**

	机器学习中的平凡贝叶斯算法


**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `Train` | ? | 训练集 |
| `Test` | ? | 测试集 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `r` | `double` | 准确度 |

**样例MR:**

> -  (train1, test1)的输出结果为r1；将train1中的每个训练样本复制一遍，加入train1中得到train2（|train2| = 2 * |train1|），test2 = test1，(train2, test2)的输出结果为r2；则有r1 == r2
> -  输入(train1,test1)输出r1,假设train1中每个训练样本的特征向量X的维度为n,对训练样本的特征向量进行维度扩展到2n,形成新的训练集train2,train2中训练样本的特征向量Y满足:1<i<=n,Y的第i分量等于X的第i分量,Y的i+n分量等于X的第i分量,相同方法从test1获得test2,输入(train2,test2)输出r2,则r1=r2 **这个没看懂,请大家帮忙看看对不对**

---

#### **题目名称:** 17#matrix transpose[矩阵转置]
**题目描述:**

	矩阵的转置 $B = A^T$

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A` | `int[][]` | N行M列矩阵 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `B` | `int[][]` | M行N列矩阵 |

**样例MR:**

> -  转置矩阵的转置矩阵等于它本身
> -  对于矩阵A,若矩阵A乘以一个整数K，则输出B也要乘以K
> -  A1的输出结果为B1，取A2、A3满足A2 + A3 = A1，则A2的输出结果为B2，A3的输出结果为B3，则有B1 = B2 + B3
> -  A1的输出结果为B1，取A2、A3满足A2 X A3 = A1，则A2的输出结果为B2，A3的输出结果为B3，则有B1 = B3 X B2
> -  输入 A， 输出 B； 令 C 为 A 的前 m-1 行， 输入 C， 输出 D； D 为 B的前 m-1 列
> -  将矩阵分块后转置再合并, 输出不变

---

#### **题目名称:** 18#max sum[连续子数组的最大和]
**题目描述:**

	计算一个数组的连续子数组的最大和

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `x` | `int[]` | 整数数组 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `s` | `int` | 输入数组的连续子数组的最大和 |

**样例MR:**

> -  将输入数组反向, 最大和不变
> -  数组中每个数乘 2, 最大和也乘以 2.

> -  输入x，输出y; 在x任意位置插入连续的数列 (a1, a2, a3, ..., ak), 使得sum(a1, ... ,ak) > y, 输出y' > y.

> -  在x中任意位置插入一个正数, 得到的输出y2 >= y

> -  将原数组x从中间某位置分开，形成两个数组，分别输入，得到s1，s2，则(s1>0?s1:0)+(s2>0?s2:0)>=s

---

#### **题目名称:** 19#String reverse[字符串反转]
**题目描述:**

	字符串反转

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `s0` | `String` | 原字符串 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `s1` | `String` | 将原字符串反转后的字符串 |

**样例MR:**

> -  字符串反转的反转等于它本身
> -  s1 反转输出 s1’, s2 反转输出 s2’, s1s2 反转输出 s2’s1’
> -  输入s1, 输出s2, 将s1和s2拼接得到s3, 输入s3得到s4, s3==s4

---

#### **题目名称:** 20#Binary Search Tree[二叉搜索树]
**题目描述:**

	根据输入序列构建二叉搜索树

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `x` | `int[]` | 要构造二叉搜索树的整数数组 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `T` | 使用数组保存的二叉搜索树 |

**样例MR:**

> -  交换比第一个元素大的第一个元素和比第一个元素小的第一个元素, 构造的二叉搜索树相同.【其实就是交换根节点的左右子节点的输入顺序】

> -  将每个输入乘-1 所得输出的二叉搜索树的每个结点乘-1后与原树对称
> -  输入x, 输出y, 将x的每个元素乘以2得到x1, 输入x1输出y1, y1每一个元素是y中相应元素的2倍

---

#### **题目名称:** 21#minimal spanning tree[最小生成树]
**题目描述:**

	求输入无向连通图的最小生成树的总cost


**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 无向连通图 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `c` | `double` | 输入UDG最小生成树的总cost |

**样例MR:**

> -  向图G中任意添加一条边得到G', 输入G'输出c', c' <= c
> -  添加一个节点，向原图任意节点引一条权值为k的边，则输出c+k
> -  输入G，输出c，从G中任意删除一条边e得到G'，若G'仍为无向连通图，那么输入G'，输出c'，c'>=c；若G'不为无向连通图，则G'可以分为两个无向连通图，G1和G2，那么令边e的cost为cost(e)，输入G1，输出c1，输入G2，输出c2，有c1+c2+cost(e)=c。

---

#### **题目名称:** 23#Euler Circle[欧拉回路]
**题目描述:**

	判断一个图是否存在[欧拉回路](http://baike.baidu.com/link?url=N5-JWNqLWsG27z4UD8ImaN8Bwn4lyJ2WcFD3Up3M4StgcZwF1LaNt6k3xzl3INsRc8TOAXVnNnzVyBzKmI6npK#1)

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 无向连通图(不包含两个端点都是同一个点的边) |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `boolean` | `TRUE`代表存在, `FALSE`代表不存在 |

**样例MR:**

> -  先创建两个新点，两点相连。取图中任意一点，分别与这两个新节点相连，作为新图输入，结果和原图相同。
> -  1. 若G为非平凡图，从G中任取两点u, v，增加两个点的集合{a1,a2,...,am}和{b1,b2,...,bn}(m, n ≥ 1)，构造两条路径：(v a1 a2  ... am u) 与(u  b1   b2  ...  bn  v)，得到G1；输入G1，则输出不变。

---

#### **题目名称:** 25#connected graph[连通图]
**题目描述:**

	判断输入的无向图G是不是[连通图](http://baike.baidu.com/link?url=yn3IE9ZrLoHowA0NvfLsHF9TnCv2gnj_VNJZbsJ2nIXRHHVQGOfiWzos0mFH2e7Ca1CCytEYdZykpVinqUL1dq#1)

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 无向图,至少含2个点 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `boolean` | `TRUE`代表是, `FALSE`代表不是 |

**样例MR:**

> -  输入 G, 若输出 true, 任意添加一个边, 输出仍为 true; 若为 false, 删除一边仍为 false.
> -  输入G，输出y; 向G中增加一个节点，但不添加边，输出y'=FALSE;
> -  若 G 不连通，则 G 的补图 G'连通;若G连通则G的补图不连通.
> -  输入G，输出为y；从G中任取一点v，删去与它相邻的所有边，得到G1，输入G1，得到y1；若y == false，y1 == false；若y == true，y1 == false。
> -  向G中增加一个结点， 并增加此节点到其他所有节点的边， 得到G’， 输入G’， 输出true
> -  输入G,输出y ; 输入G',输出y';将G和G'合并后任意添加一条边连接G和G'的边得到G''; 输入G'',输出y'';y'' = y & y'
> -  在G中增加一个节点，并随机和原图中某一结点相连，结果不变。
> -  输入G，输出y，在G中添加一个顶点v，并在G与v之间增加一条边，得到G'，输入G'，输出y'，若y'=y。

---

#### **题目名称:** 26#words replacement[单词替换]
**题目描述:**

	将输入的一长串字符串中出现的单词替换为另一个单词(不进行递归替换)

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `s0` | `String` | 原字符串 |
| `s1` | `String` | 被替换的单词 |
| `s2` | `String` | 替换的单词 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `d` | `String` | 完成替换后的新字符串 |

**样例MR:**


> -  输入s0，s1，s2，输出d；输入s0，s1，s1|s1（拼接），输出d0；输入d0，s1|s1，s2，输出d1。d == d1。
> -  输入s0，s1，s2，输出d，输入s1s0，s1，s2，输出d'=s2d。
> -  输入s0，s1，s2，输出d；输入d,s2,s1输出d1,则s0=d1;

---

#### **题目名称:** 27#candy eating[吃糖果问题]
**题目描述:**

	一次吃1块或者一次吃2块，共吃N块，有多少种吃法？

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `n` | `int` | 糖果总数(n > 0) |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `int` | 吃法总数 |

**样例MR:**

> -  n颗糖果的吃法总数加上n+1颗糖果的吃法总数等于n+2颗糖果的吃法总数
> -  记 F（N）为吃 N 块糖方法总数，则有
[很多性质](http://wenku.baidu.com/link?url=khImFf37hR5ezG6AhJ5izpn91MzRjpVc2zzhRv99lkytFXP_m8yHCdCFz9BYjZ9SloEF_JHVhbq196Vkee88AATXCJMJs0IEzwz4-TSOWTK)，要把 F（N）换成 f（N+1）**注:因为全是网上找的而且没有自己整理所以记1/4, 也就是17/4, 4条**

---

#### **题目名称:** 33#plalindrome[最长回文子序列]
**题目描述:**

	输出给定字符串中最长的回文子序列

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `s` | `String` | 原字符串(保证只有一个最长回文子序列) |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `p` | `String` | 原字符串中的最长回文子序列 |

**样例MR:**

> -  将原字符串反向, 输出不变
> -  输入 s，输出 p; 输入 s[0:len(s)-2] (if len(s) = 1, s = null)，输出 p' , p' == p or p' == p[0:len(p)-1] or p' == p[1:len(p)-1].
> -  假设输入包含n个字符的字符串s[n+1], 输出y1;那么，任取一字符c, 间断地往x的元素间插入c，即形成新字符串char S[] = {c, s[0], c, s[1], c, s[2], c, ......, c, s[n], c}, 输出y2，则y2 > y1.
> -  输入s，输出p，任选一个字符a，重复a组合为一个字符串s'，这个s'全部由a组成，并且len(s') = len(p)+1，那么输入ss'，输出p'，则len(p')>=len(p)+1。
> -  输入s，输出p，输入spp,输出p’，len(p’)>=2len(p);
> -  对原字符串S头尾各添加一个相同的字符a,构成输入S'=aSa,则S'的输出结果>=S的输出结果

---
#### **题目名称:** 32#sort[数组排序]
**题目描述:**

	输入一个乱序数组,对数组进行排序后输出

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A1` | `int[]` | 待排序的数组 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A2` | `int[]` | 排好序的数组 |

**样例MR:**

> -  输入打乱顺序后得到的结果相同

> -  乘以二

---

#### **题目名称:** 35#inverse number[逆序对]
**题目描述:**

	输入一个整数数组, 输出数组中的[逆序对](http://baike.baidu.com/view/689576.htm#1)数

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A` | `int[]` | 乱序无重复整数数组 |
| `n` | `int` | 保证一定为A的长度, 方便大家描述数组长度 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `c` | `int` | 数组中包含的逆序对数 |

**样例MR:**

> -  将输入数组反转，得到的逆序对数加上原来的逆序对数之和是n*(n-1)/2,这里的n是数组的长度
> -  输入A，输出n 交换A[0]与A[1]，输出n'。n-1<=n'<=n+1.
> -  设A长度为n， 在A前面增加一个比A中最大元素大的元素， 得到 A’， 输入 A’， 输出 c’， c’ = c + n;设A长度为n , 在A后面增加一个比A中最小元素小的元素，得到A';输入A'，输出c', c' = c + n

> -  输入A，n,输出c,将A中每个元素乘以k(k>0)得到A1,那么输入A1,n,输出c1,那么c1 = c
> -  设A长度为n， 在A后面增加一个比A中最大元素大的元素， 得到 A’， 输入 A’， 输出 c’， c’ = c;设A长度为n , 在A前面增加一个比A中最小元素小的元素，得到A',输入A'，输出c', c' = c
> -  输入A, n,输出c,将A中每个元素乘以k(k<0)得到A1,那么输入A1,n,输出c1,那么c1 + c = n*(n-1)/2
> -  假设输入A, 输出y1; 输入B, 输出y2; 使得min(B)>max(A);那么输入AB, 则输出y1+y2.
> -  在A中任意位置插入一个整数，得到的逆序对数>=原来的逆序对数

---

#### **题目名称:** 39#merge[数组合并]
**题目描述:**

	把两个递增数组合并为一个递增数组

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A1` | `int[]` | 递增的整数数组 |
| `A2` | `int[]` | 递增的整数数组 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `C` | `int[]` | 两个整数数组合并之后的递增数组 |

**样例MR:**

> -  对于对于输入A1,A2分别取负然后反转得到B1,B2,  合并B1和B2的结果再取负反转与原来的结果相同
> -  输入A1[0:m]，A2[0:n]，输出C 令x=max(A1[m-1], A2[n-1])，输入[A1 x]，[A2 x]，输出C'==[C x x];输入A1[0:m]，A2[0:n]，输出C 令x=min(A1[m-1], A2[n-1])，输入[x A1]，[x A2]，输出C'==[x x C].
> -  对于输入（A1, A2），输出为c，将A1，A2中的每个元素取负作为输入，得到输出c’ ,将c’逆序得到c’’，则任意c[i]+c’’[i]=0
> -  输入A1, A2, 输出C。取 A1 前 k 项组成数组 B1，后n-k项组成B2。输入 B1 A2 ，输出 D1；输入D1 B2， 输出D2， D2 == C
> -  设一个int型变量k比A1和A2中所有元素都要小;将这个元素单独构成一个数组A3;输入A1 , A3，输出C;输入C , A2,输出D;D的第一个元素即为k
> -  输入（A1，A2），输出C，输入（A2，A1），输出C'，C' == C
> -  对于输入（A1, A2），输出为C1，将A1，A2中的每个元素乘k(k>0)，得到A3, A4 ,输入A3,A4得到C2,那么C2 = C1 * k(每个元素都乘k)
> -  输入A1，A2，输出C，将C从中间任意位置截断为两个数组C1和C2，输入C1，C2，输出C'，C'=C。

---

#### **题目名称:** 44#max matching of bigraph[二部图的最大匹配]
**题目描述:**

	使用匈牙利算法求二部图的最大匹配

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 二部图 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `P` | `map<int, int>` | 二部图的最大匹配 |

**样例MR:**

> -  输入G的到输出为p;从G中任意删掉一个点，并将与此点相关的所有边删除，形成新的图G';输入G'，输出p';p-1<=p'<=p
> -  新建一个节点，向图中任意一个节点引一条边，将得到的新图输入，则p'>=p
> -  输入G，输出P，G中分为部1和部2，P中指出了匹配中的点，那么在部1增加一个点v'，然后选择部2中的一个出现在P的匹配中的点v，在v和v'中增加一条边，然后将图G变为了G'，现在输入G'，输出P'，|P|=|P'|。
> -  输入G，输出P，G中删除不在P内的任意一条边，则输出不变

---

#### **题目名称:** 46#max vertex independent set[最大点独立集]
**题目描述:**

	求图的最大点独立集(保证唯一)

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 连通图 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `Y` | `int[]` | 连通图的最大点独立集 |

**样例MR:**

> -  输入G，输出为y；向G中添加一个新点v，该点与G中所有顶点建立边，得到G1；输入G1，的到输出y1； y == y1
> -  输入G ,输出y;从G中任意删掉一个点， 并将与此点相关的所有边删除，形成新的图G';输入G',输出y';y-1<=y'<=y
> -  新建一个节点，向图中任意一个节点引一条边，将得到的新图输入，则Y'>=Y
> -  假设输入G，输出y1；减去G的一条边得到新图G2，输入G2，输出y2，则 y2 >= y1.假设输入G，输出y1；增加G的一条边得到新图G2，输入G2，输出y2，则 y2<= y1.
> -  输入G,输出为y;得出G的补图G’,输入G’,输出为y’,y!=y’.

---

#### **题目名称:** 47#domination set[支配集]

**题目描述:**

	连通图的点支配集

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 连通图 |
| `V` | `int[]` | 保存了点标号的数组,代表点的集合 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `Y` | `boolean` | `FALSE`代表V不是G的点支配集, `TRUE`代表V是G的点支配集 |

**样例MR:**

> -  在V集合点中，有一点X，增加任意一个与X相连的点A，得到的新集合V'，仍为点支配集。
> -  在G图中选择一个原来不是V集合中的点A进入集合V，得到的新集合V'，仍为点支配集。
> -  在G中增加一个点x，增加点x与G中原有的所有的点的边，得到G’，若(G,V)=y1,(G’,V)=y2,则y1=y2

---


**题目描述:**

	求连通图的一个点支配集

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 连通图 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `Y` | `int[]` | 连通图的一个点支配集, 点标号从小到大排列 |

**样例MR:**





---

#### **题目名称:** 48#vertex covering set[点覆盖集]
**题目描述:**

	连通图的点覆盖集

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 连通图 |
| `V` | `int[]` | G的一个点集 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `Y` | `boolean` | `FALSE`代表V不是G的点覆盖集, `TRUE`代表是 |

**样例MR:**

> -  在V集合点中，有一点X，增加任意一个与X相连的点A，得到的新集合V'，仍为点覆盖集。
> -  在G图中选择一个原来不是V集合中的点A进入集合V，得到的新集合V'，仍为点覆盖集。
> -  在G中增加一个点x，增加点x与G中原有的所有的点的边，得到G’，V’=[V,x]若(G,V)=y1,(G’,V’)=y2,则y1=y2

---


**题目描述:**

	求连通图的一个点覆盖集

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 连通图 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `int[]` | 连通图的一个点覆盖集, 点标号从小到大排列 |

**样例MR:**


> -  建立新点v1，与图中任一点（记为v0）相连，将新图输入。则v1或v0一定至少一个出现在输出中。

---

#### **题目名称:** 49#edge coloring[边染色]
**题目描述:**

	输入连通图，求对它进行边染色所需要的最少颜色数目

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 连通图 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `c` | `int` | 对输入的连通图进行边染色所需要的最少的颜色数 |

**样例MR:**


> -  输入G，输出c。新建一个节点，与图中任意某一节点v0建立边。输出c+1（当且仅当原图中的v0度为c）或c

---

#### **题目名称:** 50#vertex coloring[点染色]
**题目描述:**

	输入连通图，求对它进行点染色所需要的最少颜色数目

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 连通图,至少含2个点 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `c` | `int` | 对输入的连通图进行点染色所需要的最少的颜色数 |

**样例MR:**

> -  输入G，输出为y；向G中添加一个新点v，该点与G中任意的一点建立边，得到G1；输入G1，得到输出y1； |y| == |y1|

> -  输入G得到c。加入一个新节点，和原图所有节点相连，记为G'。输入G'，输出c'，c' = c+1

---

#### **题目名称:** 51#max clique[最大团]
**题目描述:**

	输入连通图，求它的最大[团](http://baike.baidu.com/subview/70497/9861224.htm#viewPageContent)
	(保证最大团唯一)

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 连通图 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `Y` | `int[]` | 连通图的最大团, 标号按从小到大排序 |

**样例MR:**

 > -  输入图G，输出为Y。新建一节点，编号为n（n大于所有现存节点），建立新节点到G中所有节点的边（或只建立到Y中所有节点的边）。将新图G'输入，得到输出Y'，Y' == Y.append(n)
> -  若G为非平凡图，取一点v，与G中任意一点u建立边，得到G1；输入G1，输出为Y1；Y == Y1
> -  若输入为G,输出为Y;得出G的补图G’,输入G’,输出为Y’,则Y’ != Y(即两个数组中元素构成的标号集合不等价)
> -  删掉G中度最大的点和其关联的边,构成G',则G'的输出点数小于等于G的输出点数.

---

#### **题目名称:** 52#planar graph[可平面图]
**题目描述:**

	输入连通图，判断它是不是[可平面图](http://ws.nju.edu.cn/courses/gt/11.pdf)

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `UDG` | 连通图 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `boolean` | `TRUE`代表是可平面图, `FALSE`代表不是可平面图 |

**样例MR:**


> -  输入G，输出为y；令G1为G的对偶图，输入G1，输出y1；则有y == y1
> -  对于两个可平面图A和B，选取A中一点x，B中一点y，将其相连，构成一个新的图形C，C仍为可平面图。

---

#### **题目名称:** 53#reverse arc[反向弧]
**题目描述:**

	输入有向图，计算其中[反向弧](http://acm.sjtu.edu.cn/w/images/4/49/%E5%9B%BE%E8%AE%BA-%E7%BD%91%E7%BB%9C%E6%B5%81.compressed.pdf)的对数

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `DG` | 连通图 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `c` | `int` | 图中反向弧的对数 |

**样例MR:**

> -  输入G，输出C，选取G中一条有向边e，e从v1到v2，且v2到v1不存在边，在G上增加一条有向边e'，e'从v2到v1，得到G'，则输入G'，得到C'，C'=C+1。
> -  输入G，输出C，将G中所有边的方向反一下（即原v1->v2,现v2->v1），得到G’,输入G’，输出C’，则C=C’

---

#### **题目名称:** 56#directed tree[有向树]
**题目描述:**

	判断输入的图是不是[有向树](http://baike.baidu.com/view/2551504.htm)

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `DG` | 有向图 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `boolean` | `TRUE`代表是有向树, `FALSE`代表不是有向树 |

**样例MR:**

> -  输入G，输出为y；向G中添加一个新点v，该点与G中任意的一点u建立有向边<u, v>（由u指向v），得到G1；输入G1，得到输出y1； y == y1
> -  对于图G,若向G中添加一个点v,不添加任何边,得到G',输入G,输出为false
> -  假设输入G，输出y;那么，给G添加一个新点和任意两条新边得到新图G2，输入G2，输出false.


---

#### **题目名称:** 57#Euler Digraph[Euler有向图]
**题目描述:**

	判断非平凡弱连通有向图是不是[Euler有向图](http://baike.baidu.com/view/143349.htm)

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `DG` | 非平凡弱连通有向图(不存在入点和出点相同的边) |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `boolean` | `TRUE`代表是Euler有向图, `FALSE`代表不是Euler有向图 |

**样例MR:**

> -  在G中添加两个点u,v 取G中任意点p 连接u->p p->v v->u 输出不变
> -  所有边方向取反，输出不变
> -  若G为非平凡图，从G中任取两点u, v，增加两个点的集合{a1,a2,...,am}和{b1,b2,...,bn}(m, n ≥ 1)，构造两条路径：(v->a1-> a2 ->... ->am->u) 与(u-> b1 -> b2 -> ... -> bn -> v)，得到G1；输入G1，则输出不变.

---

#### **题目名称:** 58#nameking of tournament[竞赛图中的王]
**题目描述:**

	求输入的[竞赛图](https://en.wikipedia.org/wiki/Tournament_(graph_theory))中的王

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `DG` | 有向图(竞赛图, 边从winner出发指向loser) |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `int` | 竞赛图中王的标号(有多个的时候输出标号最小的) |

**样例MR:**

> -  对于图G，得到结果y1，将图G中所有的有向边反向，得到G1；输入G1，得到y2；有y1 != y2
> -  增加一个点u 并新增路径从每个结点到u 则输出不变
> -  任意选一图，添加一节点，编号为n，并让其指向其余所有节点，构成图G，输入图G，输出n。

---

#### **题目名称:** 59#root tree[根树]
**题目描述:**

	判断输入的有向树是不是[根树](http://jpkc.fudan.edu.cn/picture/article/235/0d/97/a3e064504a53aa836d06b08b740a/2b82b79a-021a-4a64-b2ca-e2eb503a2ef9.pdf)，如果是，输出树根节点，如果不是，输出-1

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `DG` | 有向图(有向树) |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `int` | 如果等于`-1`, 说明不是根树, 否则为树根节点标号 |

**样例MR:**

> -  给G中添加一结点 V， 并从原G中节点向 V 增加一条有向边， 得到新树 G’。输入G和G’得到的输出相同
> -  在有向图中任意新增一条边，若原输出！=-1 则输出应为-1 若输出为-1 则仍是-1
> -  输入G，输出y，在G中增加一个点v，在G中找到入度为0的节点root，增加一条从v到root的有向边，得到新图G'，输入G'，输出y'，则y'=y。
> -  输入G1，G2，分别输出y1,y2，找到G2中入度为0的点v,对于G1中任意一点u，增加有向边u->v，得到新图G3，输入G3，输出y3，则y3=y1&y2

---

#### **题目名称:** 61#precode of binary tree[二叉树的二元前缀码]
**题目描述:**

	输入一个二叉树，输出这个二叉树对应的[二元前缀码](http://netclass.csu.edu.cn/NCourse/hep084/part4/chapter16/16_03_03_01.htm)

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `T` | `DG` | 二叉树 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `s` | `String` | 跟二叉树对应的二元前缀码 |

**样例MR:**

> -  输入二叉树T，输出s，将T中任意节点左右子节点交换，输出s'，则strlen(s)==strlen(s')

---

#### **题目名称:** 62#huffman[huffman算法求最优二叉树]
**题目描述:**

	输入权值数组，构造最优二叉树

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `w` | `int[]` | 权值数组 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `T` | `int[]` | 数组形式的最优二叉树 |

**样例MR:**

> -  输入w，输出T 输入[w sum(w)]，输出T'。T'的左子树==T or T'的右子树==T。输入W，输出T，令数x>= sum(W)，输入[W x]，输出T'，T'左右子树分别是叶结点x和T
> -  w 中每个元素乘以正整数k，得到 w’， 输入 w’，输出 T’， T’ 中每个元素为 T中对应位置元素的k倍
> -  添加一个权值为0的节点后输入，则这个节点一定出现在树的最底端

---

#### **题目名称:** 63#ford-fulkerson[最大流问题的ford-fulkerson算法]
**题目描述:**

	输入网络和起点，终点，求网络中从起点到终点的最大流

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `G` | `WDG` | 带权有向图 |
| `a` | `int` | 起点标号 |
| `b` | `int` | 终点标号 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `c` | `double` | 从起点到终点的最大流的值 |

**样例MR:**


> -  给G中添加一结点 V，标号v， 并从标号为 b 的结点向V增加一条有向边，权为w(w>c)， 输入 G'，a，v，输出 c;给G中添加一结点 V，标号v， 并从标号为 b 的结点向V增加一条有向边，权为w(w<c)， 输入 G'，a，v，输出 w
> -  输入(G,a,b)，输出c;添加一条a指向b的边，权值为k，输出c+k

---

#### **题目名称:** 66#heap building[建堆]
**题目描述:**

	输入整数数组，建立最大堆

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A` | `int[]` | 用于建堆的整数数组 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `H` | `int[]` | 数组形式的最大堆 |

**样例MR:**

> -  输入A，输出H，假设长度为n。 输入[A min(A)]，输出H'。H'[0:n/2-1]==H[0:n/2-1]。
> -  对于输入A，输出H，将输入A乘K得到A'，输入A'，输出H'，那么H'等于H乘K;输入A，输出H，将A中所有数乘以2，得到数组A'，输入A'，输出H'，将H'中每个数除以2，位置不变得到数组H''，则H''=H。
> -  输入A，输出H，H的长度为n,输入H[1:n-1],得到H’,则H’[0]=H[1] or H[2]

---

#### **题目名称:** 68#red black tree[红黑树]
**题目描述:**

	将输入的数组建成[红黑树](https://zh.wikipedia.org/wiki/%E7%BA%A2%E9%BB%91%E6%A0%91)

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A` | `int[]` | 用于建红黑树的整数数组 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `T` | `int[]` | 建成的红黑树的前序遍历 |

**样例MR:**

> -  将A每个元素+1，作为A'输入，得到的T'较T，每个元素大1;将A每个元素乘k(k>0)得到A'输入，得到的T'较T，每个元素是T的k倍

---

#### **题目名称:** 70#B-tree[B树]
**题目描述:**

	将输入的数组建成B-树

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A` | `int[]` | 用于建B-树的整数数组 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `T` | `int[]` | 建成的B-树的前序遍历 |

**样例MR:**


> -  将A每个元素+1，作为A'输入，得到的T'较T，每个元素大1;将A每个元素乘k(k>0)得到A'输入，得到的T'较T，每个元素是T的k倍

---

#### **题目名称:** 72#number of prime[素数个数]
**题目描述:**

	求小于等于输入正整数的素数个数

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `n` | `int` | 正整数 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `c` | `int` | 小于等于输入正整数的素数个数 |

**样例MR:**

> -  对于一个大于2的输入，如果是奇数，那么对它加1，结果不变；如果是偶数，那么对它减1，结果也不变
> -  输入n，输出c，输入10000*n，记为n'，输出c'。则(c - (n / ln(n)))/n >= (c' - (n' / ln(n')))/n'（由素数定理） **这个定理不懂...大家帮忙看看这个对不对** (另[素数计数函数](https://zh.wikipedia.org/wiki/%E7%B4%A0%E6%95%B0%E8%AE%A1%E6%95%B0%E5%87%BD%E6%95%B0)这份资料里面都是不完整的表述或者不精确的表述,因此不计入提交)
> -  输入n1,得到输出c1,那么令n2 = n1 * n1,那么输入n2,得到c2,那么若c2>=c1
> -  假设输入x, 输出y;那么，输入 x + 1, 当x+1时输出y或输出y+1;设输入x, 输出y;那么，输入 x + 2, 当x+2时输出y或输出y+1
> -  分别输入n和2n,则2n的输出一定大于n的输出(n到2n之间一定存在素数,包含端点)

---

#### **题目名称:** 74#line segment intersection[线段相交]
**题目描述:**

	判断两条线段是否相交，如果相交，输出交点的位置，如果不相交，输出(INF, INF)

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `x11` | `double` | 第1条直线上第1个点的横坐标 |
| `y11` | `double` | 第1条直线上第1个点的纵坐标 |
| `x12` | `double` | 第1条直线上第2个点的横坐标 |
| `y12` | `double` | 第1条直线上第2个点的纵坐标 |
| `x21` | `double` | 第2条直线上第1个点的横坐标 |
| `y21` | `double` | 第2条直线上第1个点的纵坐标 |
| `x22` | `double` | 第2条直线上第2个点的横坐标 |
| `y22` | `double` | 第2条直线上第2个点的纵坐标 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `x` | `double` | 交点的横坐标 |
| `y` | `double` | 交点的纵坐标 |

**样例MR:**




> -  对于所有输入的坐标取负，得到的结果为-x,-y
> -  对于所有输入的坐标 x 取负，y 不变，得到的结果为-x, y
> -  对于所有输入的坐标 x 不变，y 取负，得到的结果为x, -y
> -  将所有输入点的 x 和 y 坐标对换， 新输出为（y，x）
> -  对所有x，y 都乘2 所得结果不变
> -  对于输入，所有的坐标X加d，若输出结果为INF，那么结果还是INF，否则，x加d,坐标y不变.
> -  对于输入，所有的坐标y加d，若输出结果为INF，那么输出还是INF，否则输出结果x不变，坐标y加d
> -  先进行一次输入，若结果为不相交，分别取两线段中点，中点与两个端点构成了两个“子线段”，任取L1上的子线段和L2上的子线段输入，结果必为(INF, INF)若结果为相交，则交点与四个端点构成4个子线段（当交点与端点重合时，子线段缩为一个点，这样并不影响最终结果），然后从这4个子线段中任取两线段输入，结果必定还为原交点。
> -  假设输入(x11,y11),(x12,y12),(x21,y21),(x22,y22), 输出（x,y);令xij_new = xij*cosA + yij*sinA，yij_new = yij*cosA - xij*sinA, ij分别为11,12,21,22，其中A使得cosA,sinA均不为0。这相当于在做整个坐标系的旋转, 输入(x11_new, y11_new),(x12_new, y12_new),(x21_new,y21_new),(x22_new,y22_new),输(x_new,y_new),则x_new = x*cosA + y*sinA, y_new = y*cosA - x*sinA.(若(x,y)==(INF,INF),输出仍为(INF,INF))
> -  对(x11,y11),(x12,y12)，我们可以确定第一条直线斜率(y12-y11)/(x12-x11)，对(x12,y12)做修改，x12+1，y12+(y12-y11)/(x12-x11)得到新的点，即把(x11,y11)，(x12+1,y12+(y12-y11)/(x12-x11))，(x21,y21)，(x22,y22)输入，输出x，y不变。
> -  对(x21,y21),(x22,y22)，我们可以确定第二条直线斜率(y22-y21)/(x22-x21)，对(x22,y22)做修改，(x22+k，y22+(y22-y21)/(x22-x21)*k)得到新的点，即把(x11,y11)，(x12,y12)，(x21,y21)，(x22+k，y22+(y22-y21)/(x22-x21)*k)输入，输出x，y不变。

---

#### **题目名称:** 77#stack game[栈]
**题目描述:**

	输入2个数组, 判断后一个数组是否可以通过前一个数组入栈出栈获得. 注意: 元素入栈的顺序必须跟第一个数组原本的排列顺序相同, 且每一个元素只能入栈一次.

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `A` | `int[]` | 第1个无重复数组 |
| `B` | `int[]` | 第2个无重复数组 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `y` | `boolean` | `TRUE`代表第2个数组可以通过第1个数组入栈出栈得到, `FALSE`代表不可以 |

**样例MR:**



> -  对于输入（A，B），输出为y,那么对于任意序列C，C的反向为C'，那么输入（CA，C'B），输出为y1,则y等于y1
> -  将A，B数组每个元素加上某定值k，再次输入，结果相同
> -  对于输入（A，B），输出为y,那么对于任意序列C，C的反向为C'，在A的任意位置插入C，在B的对应位置插入C’，得到输入(A’,B’),输出为y1，则y=y1
> -  令B'为B的倒序,A'为A的倒序,以(B',A')作为输入,输出与原输出相同.

---

#### **题目名称:** 82#hex convert[进制转换]
**题目描述:**

	将十进制的正整数转换为二进制

**题目输入:**

| 输入参数 | 类型 | 说明 |
| -------- | ---- | ---- |
| `x` | `int` | 十进制正整数 |

**题目输出:**

| 输出结果 | 类型 | 说明 |
| -------- | ---- | ---- |
| `s` | `String` | 二进制01串 |

**样例MR:**

> -  输入 x 乘以 2, 则输出 s 后面补 1 个零.
> -  输入x，输出s 输入x+1，输出s'，s与s'的最低位不同
> -  输入x， 输出s； s的位数为k，输入 2^k-1-x， 输出s’； s 和 s’ 对应的位置上的数相加为1（位数不足用0补足）
> -  输入x，输出s，其中s的长度为l，输入x + 2^l，输出为strcat("1",s)
> -  输入 x1,得到输出s1,将x1除以 2(余数舍去)得到x2, 则输入x2输出 s2, s2等于s1右移一位.
> -  将十进制数X，做log2X的运算后向下取整得到Y，Y+1即为X二进制转化后输出的位数.
> -  令S'=S*2^k,则S'的的输出比S尾部多了k个0
> -  令S'=S/2^k,则S'的输出应为S右移k位

---

