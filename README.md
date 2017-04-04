# 计算流体力学 Computational Fluid Dynamics

## 主要内容

- [前言](#preparation) 
- [推荐学习路线](#learning_route) 
  - [数学基础初级](#math_basic)
  - [计算流体力学初级](#CFD_basic)
  - [数学基础中级](#math_median)
  - [计算流体力学中级](#CFD_median)
  - [程序语言能力](#programming_basic) 
  - [实战练习](#practice_basic)
- [推荐书籍列表](#booklists)


----

<h2 id="preparation">前言</h2>
深刻认识到学习是按部就班来的，步步为营、稳扎稳打。

---

<h2 id="learning_route">推荐学习路线</h2>
<h3 id="math_basic">数学基础初级</h3>

课程 | 机构 | 参考书 | Notes等其他资料
:-- | :--: | :--: | :--:
[单变量微积分](http://open.163.com/movie/2006/8/M/L/M6GLI5A07_M6GLJH1ML.html) |  MIT | [Calculus with Analytic Geometry](https://www.amazon.com/exec/obidos/ASIN/0070576424/ref=nosim/mitopencourse-20)  | [链接](https://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/) 
[多变量微积分](http://open.163.com/special/opencourse/multivariable.html)  |  MIT | [Multivariable Calculus](https://www.amazon.com/exec/obidos/ASIN/0130339679/ref=nosim/mitopencourse-20) | [链接](https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/)
[线性代数](http://open.163.com/special/opencourse/daishu.html)| MIT | [Introduction to Linear Algebra](http://math.mit.edu/~gs/linearalgebra/) |  [链接](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/study-materials/)
数值分析|| [数值分析](https://www.amazon.cn/dp/B00JL5W79W/ref=sr_1_1?ie=UTF8&qid=1488892372&sr=8-1&keywords=%E6%95%B0%E5%80%BC%E5%88%86%E6%9E%90)

---
<h3 id="CFD_basic">计算流体力学初级</h3>

书名 | 机构
:--: |:--:
 [Fundamentals of Aerodynamics](https://www.amazon.com/Fundamentals-Aerodynamics-John-Anderson/dp/1259129918/ref=pd_sbs_14_t_0?_encoding=UTF8&psc=1&refRID=8VCV9V3JN5CZE8P8WGDV)  | Marland 
[计算流体力学基础及其应用](https://www.amazon.cn/%E5%9B%BE%E4%B9%A6/dp/B00YG14HGW/ref=sr_1_1?ie=UTF8&qid=1488890621&sr=8-1&keywords=%E8%AE%A1%E7%AE%97%E6%B5%81%E4%BD%93%E5%8A%9B%E5%AD%A6%E5%9F%BA%E7%A1%80%E5%8F%8A%E5%85%B6%E5%BA%94%E7%94%A8)| Maryland|

---
<h3 id="math_median">数学基础中级</h3>

书名 | 机构
:--: |:--:
[数学分析新讲](https://www.amazon.cn/%E6%95%B0%E5%AD%A6%E5%88%86%E6%9E%90%E6%96%B0%E8%AE%B2-%E7%AC%AC1%E5%86%8C-%E5%BC%A0%E7%AD%91%E7%94%9F/dp/B00P7MJOZI/ref=cm_cr_arp_d_product_top?ie=UTF8)     | PKU |
[高等代数简明教程](https://www.amazon.cn/%E6%99%AE%E9%80%9A%E9%AB%98%E7%AD%89%E6%95%99%E8%82%B2-%E5%9B%BD%E5%AE%B6%E7%BA%A7%E8%A7%84%E5%88%92%E6%95%99%E6%9D%90%C2%B7%E5%8C%97%E4%BA%AC%E5%A4%A7%E5%AD%A6%E6%95%B0%E5%AD%A6%E6%95%99%E5%AD%A6%E7%B3%BB%E5%88%97%E4%B8%9B%E4%B9%A6-%E9%AB%98%E7%AD%89%E4%BB%A3%E6%95%B0%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B-%E8%93%9D%E4%BB%A5%E4%B8%AD/dp/B00P7MJOUI/ref=pd_bxgy_14_img_2?ie=UTF8&psc=1&refRID=9TZHEQS13ZEQH7XEJXRC) | PKU
[矢量分析与场论](https://www.amazon.cn/%E9%AB%98%E7%AD%89%E5%AD%A6%E6%A0%A1%E6%95%99%E6%9D%90%E2%80%A2%E5%B7%A5%E7%A8%8B%E6%95%B0%E5%AD%A6-%E7%9F%A2%E9%87%8F%E5%88%86%E6%9E%90%E4%B8%8E%E5%9C%BA%E8%AE%BA/dp/B0084XU730/ref=sr_1_fkmr1_1?ie=UTF8&qid=1488891767&sr=8-1-fkmr1&keywords=%E7%9F%A2%E9%87%8F%E5%88%86%E6%9E%90%E4%B8%8E%E5%BC%A0%E9%87%8F%E5%88%86%E6%9E%90) | 
[张量分析](https://www.amazon.cn/%E5%9B%BE%E4%B9%A6/dp/B00N9UDSHK/ref=sr_1_1?ie=UTF8&qid=1488891832&sr=8-1&keywords=%E5%BC%A0%E9%87%8F%E5%88%86%E6%9E%90) | THU
[偏微分方程及数值解](https://www.amazon.cn/%E6%99%AE%E9%80%9A%E9%AB%98%E7%AD%89%E6%95%99%E8%82%B2-%E8%A7%84%E5%88%92%E6%95%99%E6%9D%90-%E5%81%8F%E5%BE%AE%E5%88%86%E6%96%B9%E7%A8%8B%E6%95%B0%E5%80%BC%E8%A7%A3%E6%B3%95-%E5%AD%99%E5%BF%97%E5%BF%A0/dp/B007PNM9VS/ref=sr_1_7?ie=UTF8&qid=1488892479&sr=8-7&keywords=%E5%81%8F%E5%BE%AE%E5%88%86%E6%96%B9%E7%A8%8B+%E6%95%B0%E5%80%BC) |

---
<h3 id="CFD_median">计算流体力学中级</h3>

书名 | 机构
:--: |:--:
[ An Introduction to Computational Fluid Dynamics-The Finite Volume Method](https://www.amazon.com/Introduction-Computational-Fluid-Dynamics-Finite/dp/0131274988/ref=sr_1_1?s=books&ie=UTF8&qid=1488892262&sr=1-1&keywords=An+Introduction+to+Computational+Fluid+Dynamics-The+Finite+Volume+Method)| 
[COMPUTATIONAL FLUID DYNAMICS principles and Applications](https://www.amazon.com/Computational-Fluid-Dynamics-Principles-Applications/dp/0080999956/ref=sr_1_1?s=books&ie=UTF8&qid=1488891087&sr=1-1&keywords=COMPUTATIONAL+FLUID+DYNAMICS+principles+and+Applications) | 
[The Finite Volume Method in Computational Fluid Dynamics  An Advanced Introduction with OpenFOAM® and Matlab](https://www.amazon.com/Finite-Method-Computational-Fluid-Dynamics-ebook/dp/B013W6ROKW/ref=sr_1_1?s=books&ie=UTF8&qid=1488892625&sr=1-1&keywords=The+Finite+Volume+Method+in+Computational+Fluid+Dynamics++An+Advanced+Introduction+with+OpenFOAM%C2%AE+and+Matlab)  |
[Turbulence Modeling for CFD](https://www.amazon.com/Turbulence-Modeling-Third-David-Wilcox/dp/1928729088/ref=sr_1_1?s=books&ie=UTF8&qid=1488892797&sr=1-1&keywords=Turbulence+modeling+for+cfd) |
[Riemann Solvers and Numerical Methods for Fluid Dynamics: A Practical Introduction](https://www.amazon.com/Riemann-Solvers-Numerical-Methods-Dynamics/dp/3540252029/ref=sr_1_1?s=books&ie=UTF8&qid=1488892886&sr=1-1&keywords=Riemann+solver) |

---
<h3 id="programming_basic">程序语言能力</h3>

计算流体力学的核心是数学原理+程序实现，编程语言是必须的。

课程 | 参考学习链接 | 推荐书籍
:-- | :--: | :--:
C++程序语言设计| [C++语言程序设计基础](http://www.xuetangx.com/courses/course-v1:TsinghuaX+00740043_1x+2017_T1/about) | [C++ Primer(中文版)](https://www.amazon.cn/%E5%9B%BE%E4%B9%A6/dp/B00ESUIL0O/ref=sr_1_1?s=books&ie=UTF8&qid=1488893037&sr=1-1&keywords=c+primer) 
Fortran程序语言设计| [Fortran实用编程](http://v.fcode.cn/) | [Fortran95程序设计](https://www.amazon.cn/Fortran95%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1-%E5%BD%AD%E5%9B%BD%E4%BC%A6/dp/B00119CRTQ/ref=sr_1_1?ie=UTF8&qid=1488893157&sr=8-1&keywords=Fortran)

---
<h3 id="practice_basic"> 实战练习 </h3>

翼型绕流二维求解器编写，可参考 [NS-2D](https://github.com/hangsz/NS-2D)：
- 第一阶段 Euler方程求解器 ：建议对流项离散采用JST格式。时间离散可以采用 显示 Runge-Kutta法。upwind格式和隐式推进较难，以后可以再完善。
- 第二阶段 NS方程求解器：比Euler只多了扩散项，这一项离散比较简单。
- 第三阶段 采用upwind格式和隐式格式：现在要求解大型代数方程组了，当然是LU-SGS方法。
- 第三阶段 湍流模型： 建议采用SA模型，这个是一方程的，简单。湍流方程和NS方程耦合求解。
- 第四阶段 预处理： 之前的都是适合可压流，预处理之后适合全速域。
- 第五阶段 动网格...

Fortran行数：到达第四阶段代码量5000行左右

---
<h2 id="booklists">推荐书籍列表</h2>

|  参考书  | 难度 |
| :----:  |:----:| 
|   [数学分析新讲](https://www.amazon.cn/%E6%95%B0%E5%AD%A6%E5%88%86%E6%9E%90%E6%96%B0%E8%AE%B2-%E7%AC%AC1%E5%86%8C-%E5%BC%A0%E7%AD%91%E7%94%9F/dp/B00P7MJOZI/ref=cm_cr_arp_d_product_top?ie=UTF8)     |  |
| [高等代数简明教程](https://www.amazon.cn/%E6%99%AE%E9%80%9A%E9%AB%98%E7%AD%89%E6%95%99%E8%82%B2-%E5%9B%BD%E5%AE%B6%E7%BA%A7%E8%A7%84%E5%88%92%E6%95%99%E6%9D%90%C2%B7%E5%8C%97%E4%BA%AC%E5%A4%A7%E5%AD%A6%E6%95%B0%E5%AD%A6%E6%95%99%E5%AD%A6%E7%B3%BB%E5%88%97%E4%B8%9B%E4%B9%A6-%E9%AB%98%E7%AD%89%E4%BB%A3%E6%95%B0%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B-%E8%93%9D%E4%BB%A5%E4%B8%AD/dp/B00P7MJOUI/ref=pd_bxgy_14_img_2?ie=UTF8&psc=1&refRID=9TZHEQS13ZEQH7XEJXRC) | 
|  [Fundamentals of Aerodynamics](https://www.amazon.com/Fundamentals-Aerodynamics-John-Anderson/dp/1259129918/ref=pd_sbs_14_t_0?_encoding=UTF8&psc=1&refRID=8VCV9V3JN5CZE8P8WGDV)  |  |
|  [计算流体力学基础及其应用](https://www.amazon.cn/%E5%9B%BE%E4%B9%A6/dp/B00YG14HGW/ref=sr_1_1?ie=UTF8&qid=1488890621&sr=8-1&keywords=%E8%AE%A1%E7%AE%97%E6%B5%81%E4%BD%93%E5%8A%9B%E5%AD%A6%E5%9F%BA%E7%A1%80%E5%8F%8A%E5%85%B6%E5%BA%94%E7%94%A8)|  |
| [COMPUTATIONAL FLUID DYNAMICS principles and Applications](https://www.amazon.com/Computational-Fluid-Dynamics-Principles-Applications/dp/0080999956/ref=sr_1_1?s=books&ie=UTF8&qid=1488891087&sr=1-1&keywords=COMPUTATIONAL+FLUID+DYNAMICS+principles+and+Applications)| 
[ An Introduction to Computational Fluid Dynamics-The Finite Volume Method](https://www.amazon.com/Introduction-Computational-Fluid-Dynamics-Finite/dp/0131274988/ref=sr_1_1?s=books&ie=UTF8&qid=1488892262&sr=1-1&keywords=An+Introduction+to+Computational+Fluid+Dynamics-The+Finite+Volume+Method)| 
[The Finite Volume Method in Computational Fluid Dynamics  An Advanced Introduction with OpenFOAM® and Matlab](https://www.amazon.com/Finite-Method-Computational-Fluid-Dynamics-ebook/dp/B013W6ROKW/ref=sr_1_1?s=books&ie=UTF8&qid=1488892625&sr=1-1&keywords=The+Finite+Volume+Method+in+Computational+Fluid+Dynamics++An+Advanced+Introduction+with+OpenFOAM%C2%AE+and+Matlab)  | 
