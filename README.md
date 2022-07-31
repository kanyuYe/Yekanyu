# Yekanyu
叶戡语
小组成员：叶戡语
完成项目：
Impl Merkle Tree following RFC6962：运行结果截图：![IO41ZR~L~Y5)1OC )U2WPIK](https://user-images.githubusercontent.com/110303856/182012002-cdf6fe32-18c7-462c-b3c3-33d4f88b62fb
实现过程说明：
1.构建一个二叉树。其中父节点的数据字段为子节点哈希值相加后的哈希值
2.考虑树中奇数个节点的情况
3.验证节点是否在merkle tree中（通过哈希值判断）

send a tx on Bitcoin testnet, and parse the tx data down to every bit, better write script yourself
forge a signature to pretend that you are Satoshi
research report on MPT
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
