# 游戏规则
- 游戏初始有三个坑位，第一个坑位由上至下摆了n个盘子，将这n个盘子移动至其他坑位且保持他们的相对位置不变即获胜
- 要求有二：1、每次只能移动一个盘子 2、移动后大盘子不得在小盘子上面

# 核心代码
- 这个游戏在实践中如果需要多人配合完成是非常困难的，因为每个人的思路不一样，一旦断开又很难接上，一旦走错几步，就很难恢复了
- 但是在程序中使用递归是很容易解决的，就是一个层层分解的过程，核心代码不超过15行

# 可视化效果
![image](https://github.com/shadow12138/QianKunDaNuoYi/blob/master/result/result.gif)


