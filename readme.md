期末考试平时成绩gpa拆分器Excel版v0.1
1.生成一个统一指定的平时成绩gpa，并将其随机拆分为多个子项和嵌套子项。
2.若需指定平时成绩，比如从其它工作表复制过来的平时成绩，则设置代码中平时成绩为-1，然后拆分为多个子项和嵌套子项。
3.界面上需要手工指定考试成绩test列的开始列数，如b列则为2列；test列右侧的列结构不可以调整，test列左侧的列可以任意添加如学生id等
列。
4.gpa拆分分数，随机数服从均值，标准差的正太分布。标准差指定std_dev = 3。
5.代码中可设置以下变量，
'设置以下四个变量
test_score_col = 2  '考试分数的列
lower_bound = 60    '平时成绩随机数的下限值,上限值为考试成绩,若考试成绩低于此数,则平时成绩不会高于此下限
assign_gpa_score = 89 '指定的平时成绩,-1为代码不生成平时成绩
std_dev = 3 '指定标准差

for 四川xx学院
15th-Jan-2020