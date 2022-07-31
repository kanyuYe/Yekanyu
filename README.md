# Yekanyu
叶戡语
小组成员：叶戡语
完成项目：
一.Impl Merkle Tree following RFC6962：运行结果截图：(![结果](https://user-images.githubusercontent.com/110303856/182012928-2bb7442f-9e35-465a-acc5-2cc323aacaba.png))
实现过程说明：
1.构建一个二叉树。其中父节点的数据字段为子节点哈希值相加后的哈希值
2.考虑树中奇数个节点的情况
3.验证节点是否在merkle tree中（通过哈希值判断）


二.send a tx on Bitcoin testnet, and parse the tx data down to every bit, better write script yourself
具体详解见项目

三.forge a signature to pretend that you are Satoshi
运行结果截图：![image](https://user-images.githubusercontent.com/110303856/182012999-92b35849-fdbe-4316-af74-c42706998a80.png)
实现过程说明：
1.先引用一个库，导入比特币中固定的G，n等等（未找到中本聪的P=dG，故P取了一个随机值）
2.设出u，v的值
3.根据公式，建立数学关系，得到伪造的r，e，s满足对e=hash（m）的验证。


四.research report on MPT
具体详解见项目

未完成项目：
implement the naïve birthday attack of reduced SM3

implement the Rho method of reduced SM3

implement length extension attack for SM3, SHA256, etc

do your best to optimize SM3 implementation (software)

Try to Implement this scheme(below)

report on the application of this deduce technique in Ethereum with ECDSA

impl sm2 with RFC6979

verify the above pitfalls with proof-of-concept cod

Implement the above ECMH scheme

Implement a PGP scheme with SM2

implement sm2 2P sign with real network communication

implement sm2 2P decrypt with real network communication

PoC impl of the scheme, or do implement analysis by Google

Find a key with hash value “sdu_cst_20220610” under a message composed of your name followed by your student ID. For example, “San Zhan 202000460001”.

Find a 64-byte message under some k fulfilling that their hash value is symmetrical
