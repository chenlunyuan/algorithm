# algorithm

## 取模运算法则
乘法 : (a * b) % p = (a % p * b % p) % p  
加法 : (a + b) % p = (a % p + b % p) % p  
减法 : (a - b) % p = (a % p - b % p) % p  

## 快速幂
a^n : 在乘方a中，其中的a叫做底数，n叫做指数，结果叫幂。  
3^10  : 代表3的10次方幂  
= (3 * 3) * (3 * 3) * (3 * 3) * (3 * 3) * (3 * 3)  
= (3 * 3)^5  
= 9 ^ 5  
= (9 * 9) * (9 * 9) * (9) 
= 81^2 * 9^1  
= （6561^1）*(9^1)  
= 6561 * 9  
= 59049  

## 位运算替换
1、a % 2 == 1 等同 a & 1  
2、a * 2 等同 a << 1  
3、a / 2 等同 a >> 1  
