---
title: PhysRevA.68.012314
date: 2024-03-011 01:06:51
tags:
categories: 
- note

---



**I. INTRODUCTION**

- purity for Gaussian states of single-mode continuous variable systems, purity of single-mode Gaussian states

  <!--more-->

  - obvious difficulty: pure states are unavoidably corrupted by interaction with the environment
  - pure Gaussian states of continuous variable (CV) systems: coherent and squeezed-coherent states

  CV Gaussian states that are available for experiments are usually mixed states, and it becomes crucial to establish their degree of purity or mixedness determined by the environmental noise

- $\mu=\text{Tr}[\rho^2]$

  - range $\frac{1}{d}$ for a completely mixed state, 1 for a pure state

    CV systems, i.e., infinite dimensional Hilbert spaces

-  $\mu$ is a nonlinear function of the density matrix, it cannot be connected to an observable quantity if we perform repeated measurements on single copies of the state. (cannot be the expectation value of a single-system self-adjoint operator, nor can it be related to a single-system probability distribution obtained from a POVM)  纯度是密度矩阵的非线性函数，不能通过量子态的单一复制的重复测量联系到可观测量（不能是单系统自伴算子的期望值，也不能联系到从POVM获得的单系统概率分布）

  if collective measurements on two copies of the state are possible, then the purity may be measured directly 量子态的两个复制的联合测量是可以直接测量纯度的

- quantum tomography:  statistics is usually poor, since the measurement of a whole quorum of observables is needed, unavoidably leading to large fluctuations

  Gaussian states are uniquely defined by their first two statistical moments, which can be measured by the joint detection of two conjugate quadratures, 高斯态由前两个统计矩唯一确定，可以由两个共轭量的联合测量确定

- We will show that the measurement of the Q function is the optimal minimal measurement for the purity, in the sense that it is necessary and sufficient to determine $\mu$ and requires the minimum number of observables to be measured.


- single-mode radiation field, single atom: for these systems, the class of Gaussian states includes almost all the states that can be reliably produced


- the time evolution of the purity of an initial Gaussian state in a noisy channel can be uniquely expressed as a function of the initial observable parameters of the input state and of the asymptotic observable parameters of the environment




**II. PURITY OF GAUSSIAN STATES**

- Wigner representation of an arbitrary operator O

  The Wigner representation $W(\alpha)$ of the density matrix $\rho$ of a quantum state is referred to as the Wigner function of the state. Gaussian Wigner function

- parametrization of Gaussian states，applying the phase space representation of squeezing

$$
\mu=\frac{1}{2\sqrt{\text{Det}[\sigma]}}
$$

$$
\mu=\frac{1}{2 \bar n+1}
$$

- the purity of a generic Gaussian state depends only on the average number of thermal photons, as one should expect, since displacement and squeezing are unitary operations. 一个普遍的高斯态的纯度只依赖于平均热光子数，就像我们期待的那样，因为平移和压缩是幺正操作 Therefore, the measurement of the purity of a Gaussian state is equivalent to the measurement of its average number of thermal photons. 所以测量一个高斯态的纯度就相当于测量它的平均热光子数

  antinormally ordered expression

- Gaussian states may be effectively characterized as well by single-quadrature measurements obtained by balanced homodyne detection. Thus, a question arises whether or not one really needs to resort to joint measurement of two conjugate quadratures to determine the purity
- In the deep quantum regime, i.e., for small $\bar n$, fluctuations of $\mu$ become more relevant. This is not surprising, since m is a highly nonlinear function of the second-order moments.



**IV. EVOLUTION OF PURITY IN A NOISY CHANNEL**

- Let us consider the time evolution of an initial, pure or mixed, generic single-mode Gaussian state in the presence of noise and damping (and/or pumping) toward a final squeezed thermal state.

  M is the correlation function of the bath (which is usually referred to as the squeezing of the bath）

- First moments are damped through the noisy channel: this effect should be expected since it is the mathematical evidence of the absorption of the state’s coherent photons.

- the initial Gaussian state for which purity is best preserved in time must have a squeezing parameter $r_0=r_{\infty}$ and a squeezing angle, $\phi_0=\phi_{\infty}+\pi/2$ i.e., it must be antisqueezed (orthogonally squeezed) with respect to the bath)

  The net effect for the evolution of the purity is that the two orthogonal squeezings of the initial state and the bath cancel each other exactly, thus reproducing the optimal purity evolution of an initial nonsqueezed coherent state in a nonsqueezed thermal bath.











