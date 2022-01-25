# python-list_concat



python 列表叠加:


2022-01-25,12点28

python 列表叠加:
https://blog.csdn.net/pzl_pzl/article/details/106236676

a=[[1,2],[2,3]]
sum(a.tolist()) #报错,因为默认sum是对0求和
sum(a.tolist(),[]) # 返回 [1,2,2,3]  表示sum对[]进行求和操作,每一次抽取前面迭代器a.tolist()
里面的一个元素加上去.所以就返回了[1,2,2,3]

