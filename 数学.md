https://www.codecogs.com/latex/eqneditor.php	公式

https://jidugs.wrste.com/					识别

## 三角函数

| 度    | $0^{\circ}$​ | $30^{\circ}$         | $45^{\circ}$​         | $60^{\circ}$         |   $90^{\circ}$   | $120^{\circ}$        | $135^{\circ}$         | $150^{\circ}$         | $180^{\circ}$ |
| ----- | :---------: | -------------------- | -------------------- | -------------------- | :--------------: | -------------------- | --------------------- | --------------------- | ------------- |
| 弧度  |      0      | $\frac{\pi }{6}$     | $\frac{\pi }{4}$     | $\frac{\pi }{3}$     | $\frac{\pi }{2}$ | $\frac{2\pi }{3}$    | $\frac{3\pi }{4}$     | $\frac{5\pi }{6}$     | $\pi$         |
| sin x |      0      | $\frac{1}{2}$        | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{3}}{2}$ |        1         | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{2}}{2}$  | $\frac{1}{2}$         | 0             |
| cos x |      1      | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{2}}{2}$ | $\frac{1}{2}$        |        0         | $-\frac{1}{2}$       | $-\frac{\sqrt{2}}{2}$ | $-\frac{\sqrt{3}}{2}$ | -1            |
| tan x |      0      | $\frac{\sqrt{3}}{3}$​ | 1                    | $\sqrt{3}$           |      不存在      | $-\sqrt{3}$          | -1                    | $-\frac{\sqrt{3}}{3}$ | 0             |

倒数关系：sin x · cos x =1  ，cos x ·  sec x =1， tan x · cot x =1 

商数关系： tan x = $\frac{sin x}{cos x}$  ，cot x = $\frac{1}{tan x}$ = $\frac{cos x}{sin x}$​

平方关系：  $\sin^{2}x$​ + $\cos^{2}x$​ = 1 ,  $\tan^{2}x$​ +1 = $\frac{\sin^{2}x}{\cos^{2}x}$​ + $\frac{\cos^{2}x}{\cos^{2}x}$​ =$\frac{1}{\cos^{2}x}$​ =$sec^{2}x$​​

​					 $\cot^{2}x$  +1=  $\frac{\cos^{2}x}{\sin^{2}x}$ +$\frac{\sin^{2}x}{\sin^{2}x}$   =$\frac{1}{\sin^{2}x}$ = $\csc^{2}x$ 

和差化积：

积化和差：

二倍角公式：

对数运算法则： $\begin{array}{l}
\text {} \log _{a}(M N)=\log _{a} M+\log _{a} N \\
\text {} \log _{a}(M / N)=\log _{a} M-\log _{a} N \\
\text {} \log _{a}(1 / N)=-\log _{a} N \\
\text {} \log _{a} M^{n}=n \log _{a} M
\end{array}$​​

​							 $\log _{a}\left(a^{k}\right)=k$​



## 极限

连续的定义:函数在某点的极限值**等于** 函数值,那么函数在该点连续。

第一类间断点：可去（相等） ，跳跃（不相等）

第二类间断点：无穷   震荡

定义域：$  \frac{1}{x}$ $x\neq 0$  ,   $\sqrt[2]{x}$  $x\geq 0$  ,  $ln x $  x>0   ,arc sin x、arc tan x    $-1\leqslant x \leqslant 1$

奇函数 ：原点对称  f(-x)= -f(x)

偶函数： y轴对称  f(-x)= f(x)  大部分偶函数不存在反函数

f(-x)+f(x)= 0 奇

f(-x) + f(x)= 2f(x) 偶

f(x)=0 即奇函数又是偶函数

常见奇函数：$x^{2n+1 }$​   $n(\neq 0)$​ $ ,sin x ,tan x ,arc sin x ,arc tan x $​ ，$log_{a}\sqrt{1+x^{2} }\pm x$​ , $f(x)-f(-x)$​ ,

​						$\frac{e^{x}-e^{-x}}{2}$​    ，y=x

常见偶函数： $x^{2n}$​​​  $n(\neq 0)$​​​ ，$|x|$​​​  $cos x$​​​  ,常数函数 ，f(x)+f(-x) ,   $\frac{e^{x}+e^{-x}}{2}$​ ​​​

奇 $\pm $ 奇=奇		偶 $\pm$ 偶=偶			奇 $\pm $​ 偶 =非奇非偶

奇 $\ast \div$​ 奇 = 偶		偶 $\ast\div$​  偶 = 偶			奇 $\ast \div $​ 偶  = 奇 		$| 奇 |$​​=偶

${f(x)}'$ >0 增   ${f(x)}'$ <0 减  

常见有界函数	 sin x ，cos x ，arc sin x ，arc cos x，arc tan x，arc cot x

无界：y=x

等价无穷小(*可逆*  ):	$x\rightarrow 1:\quad\ln x=0 \sim x-1$​​​​	

​						$x \rightarrow 0$​ : $sec x -1=$​  $ \frac{1}{cos x}$​ $ - $​  $\frac{cos x}{cos x}$​ =$\frac{1-cos x}{cos x}$​ =$\frac{\frac{1}{2}x^{2}}{cos 0}$​ = $\frac{1}{2}x^{2}$​	

​						$tan x-x\sim \frac{x^{3}}{3}$​

 x ，sin x ，tan x ，arc sin x ，arc tan x  任意两者 差 为三阶无穷小

求函数 $f(x)=\frac{x^{3}+3 x^{2}-x-3}{x^{2}+x-6} $的连续区间, 并求极限$ \lim _{x \rightarrow 0} f(x), \lim _{x \rightarrow-3} f(x)\\
$及$\lim _{x \rightarrow 2} f(x)$​​

连续区间就是定义域用 " , " 隔开

极限定义式 方法：$\infty ^{\infty }$  : $e^{ln}$​ ​

​							     $e^{0}-e^{0}$​​  : 凑$e^{\bigtriangleup }-1\sim \bigtriangleup $​ , 一般提取减号后面的数当公因式

​								$0 *\infty  $​  : $ \frac{0}{\frac{1}{\infty}}$​  即  $\frac{0}{0}$​  。 或      $ \frac{\infty}{\frac{1}{0}}$​  即$\frac{\infty}{\infty}$​​​​ ​ 

​								$\infty-\infty$ : 有分母 先通分 。 没分母 凑 $0 *\infty  $  或者 有理化

​								$\infty^{0}$​  $0^{\infty}$​  : $e^{ln}$​ 

​								$1 ^{\infty }$ : 凑$(1+x)^{\frac{1}{x}}$ =e  , $x\rightarrow 0$​ ​

​				自变量趋向于正无穷，对数函数趋于正无穷，幂函数也趋向与正无穷，幂函数比对数函数快 

​				指数函数比幂函数快



${arc tan x}'$​​​  =

## 导数和微分

绝对值函数在等于0处不可导

初等函数定义域内连续

导数定义形式：$\begin{array}{l}
f^{\prime}\left(x_{0}\right)=\lim _{x \rightarrow x_{0}} \frac{f(x)-f\left(x_{0}\right)}{x-x_{0}} \\
\text {} f^{\prime}\left(x_{0}\right)=\lim _{\Delta x \rightarrow 0} \frac{f\left(x_{0}+\Delta x\right)-f\left(x_{0}\right)}{\Delta x} 
\end{array}$​​

n阶导公式： $\left(e^{x}\right)^{(n)}=e^{x}$​​   ,  $  \left(e^{a x+b}\right)^{(n)}=a^{n} e^{a x+b}$​​​​​​​ ​​ ,   $\left(x^{m}\right)^{(n)}=\left\{\begin{array}{l}
n !,   m=n \\
0,   m<n\end{array}\right .$​​​​

切线方程：$y-y_{0}=f{(x_{0})}'(x-x_{0})$​​​ 

法线方程：$y-y_{0}=-\frac{1}{f{(x_{0})}'}(x-x_{0})$ ​

​					$k_{法}=-\frac{1}{k_{切}}$

连续不一定可导，可导必然连续

导数公式 ：${a^{x}}'=a^{x}ln  a$   ${log_{a} x}'=\frac{1}{xlna}$

导数四则运算 ：略

连续  $ \Rightarrow  $​​​​ 可导 必要条件 ，可导是连续的必然条件

可导 $ \Rightarrow  $​​ 连续 充分条件  ，连续是可导的充分条件

偏导 :  $\left\{\begin{matrix}
F_{x} & 对x求偏导, 把y看作常数\\
F_{y} & 对x求偏导, 把x看作常数\\
\end{matrix}\right.$​​   	前提条件 $F(x,y)=0$​​

对数求导法：$\left\{\begin{matrix}
单边取对数 & 1\\
双边取对数 & 2\\\end{matrix}\right.$​​

罗尔中值定理：闭区间[a , b] 上连续  ，开区间 （a，b）可导，   f (a)=f(b)   $\exists $​  一点  使得  ${f (x)}'$​ ​​​=0

拉格朗日中值定理：闭区间[a , b] 上连续  ，开区间 （a，b）可导，使得  $\frac{f(b)-f(a)}{b-a}$ 

求单调区间：1. 求定义域  2.  一阶导等于0和不存在的点   3.  用不存在的点和等于0的店划分定义域

驻点： ${f (x)}'$ =0 

极值判定：$\left\{\begin{matrix}
先减 后增 极小值 &  \\
先增 后减 极大值& \\\end{matrix}\right.$  第二判定定理： 当${f (x)}'$ =0 时 $\left\{\begin{matrix}
 {f (x)}'' >0  &   极小值 \\ 
{f (x)}'' <0& 极大值 \\\end{matrix}\right.$ 

最值：1. 一阶导等于0和不存在的点  2. 求1中所有点的函数值 最大就是最大值 最小就是最小值

 

## 不定积分

 ${F (x)}'$ =${f (x)}$  ， $F(x)是f(x)函数$  

