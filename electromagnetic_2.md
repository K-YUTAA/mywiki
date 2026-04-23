以下では、PDFの文字化けしている「→」を **マイナス記号** と読み、
**問1は A(0,L), B(0,-L) にそれぞれ負の点電荷 (-q) が固定されている** として解きます。問題文は添付プリントの「Coulomb の法則」第2回演習です。

---

# 問1：点電荷と Coulomb の法則

## 設定

点電荷は

[
A(0,L),\qquad B(0,-L)
]

にあり、どちらも電荷は

[
-q
]

です。ここで (q>0) は電荷の大きさだとします。

観測点は (x) 軸上の点

[
P(x,0)
]

です。

Coulomb の法則をベクトルで書くと、位置 (\mathbf{r}_0) にある点電荷 (Q) が、位置 (\mathbf{r}) に作る電場は

[
\mathbf{E}
==========

kQ\frac{\mathbf{r}-\mathbf{r}_0}{|\mathbf{r}-\mathbf{r}_0|^3}
]

です。

---

## (1) (x) 軸上の電場 (\mathbf{E}(x,0))

まず、観測点の位置ベクトルを

[
\mathbf{r}=(x,0)
]

とします。

点 A の位置ベクトルは

[
\mathbf{r}_A=(0,L)
]

なので、

[
\mathbf{r}-\mathbf{r}_A
=======================

# (x,0)-(0,L)

(x,-L)
]

です。

また距離は

[
|\mathbf{r}-\mathbf{r}_A|
=========================

\sqrt{x^2+L^2}
]

です。

したがって、点 A の電荷 (-q) が作る電場は

[
\mathbf{E}_A
============

k(-q)\frac{(x,-L)}{(x^2+L^2)^{3/2}}
]

すなわち

[
\mathbf{E}_A
============

\left(
-\frac{kqx}{(x^2+L^2)^{3/2}},
\frac{kqL}{(x^2+L^2)^{3/2}}
\right)
]

です。

---

次に、点 B について考えます。

点 B の位置ベクトルは

[
\mathbf{r}_B=(0,-L)
]

なので、

[
\mathbf{r}-\mathbf{r}_B
=======================

# (x,0)-(0,-L)

(x,L)
]

です。

距離は同じく

[
|\mathbf{r}-\mathbf{r}_B|
=========================

\sqrt{x^2+L^2}
]

です。

したがって、点 B の電荷 (-q) が作る電場は

[
\mathbf{E}_B
============

k(-q)\frac{(x,L)}{(x^2+L^2)^{3/2}}
]

すなわち

[
\mathbf{E}_B
============

\left(
-\frac{kqx}{(x^2+L^2)^{3/2}},
-\frac{kqL}{(x^2+L^2)^{3/2}}
\right)
]

です。

---

全体の電場は

[
\mathbf{E}
==========

\mathbf{E}_A+\mathbf{E}_B
]

ですから、

[
E_x
===

-\frac{kqx}{(x^2+L^2)^{3/2}}
-\frac{kqx}{(x^2+L^2)^{3/2}}
]

より

[
E_x
===

-\frac{2kqx}{(x^2+L^2)^{3/2}}
]

です。

一方、

[
E_y
===

\frac{kqL}{(x^2+L^2)^{3/2}}
-\frac{kqL}{(x^2+L^2)^{3/2}}
============================

0
]

です。

したがって答えは

[
\boxed{
\mathbf{E}(x,0)
===============

\left(
-\frac{2kqx}{(x^2+L^2)^{3/2}},
0
\right)
}
]

です。

---

## 物理的な意味

上下対称に負電荷が置かれています。

点 (P(x,0)) において、上の電荷 A からの電場と下の電荷 B からの電場を考えると、(y) 成分は互いに逆向きなので打ち消し合います。

一方、(x) 成分は同じ向きになります。

負電荷が作る電場は、負電荷の方向を向きます。したがって、たとえば (x>0) の点では、電場は左向き、つまり負の (x) 方向になります。実際に

[
E_x
===

-\frac{2kqx}{(x^2+L^2)^{3/2}}
]

なので、(x>0) なら (E_x<0) です。

---

# 問1 (2)：(E_x(x,0)) のグラフ

求めた式は

[
E_x(x,0)
========

-\frac{2kqx}{(x^2+L^2)^{3/2}}
]

です。

グラフを描きやすくするために、無次元化します。

[
X=\frac{x}{L}
]

とおくと、

[
x=LX
]

なので、

[
E_x
===

-\frac{2kqLX}{(L^2X^2+L^2)^{3/2}}
]

# [

-\frac{2kqLX}{L^3(X^2+1)^{3/2}}
]

# [

-\frac{2kq}{L^2}
\frac{X}{(X^2+1)^{3/2}}
]

です。

したがって、

[
\frac{E_x}{kq/L^2}
==================

-\frac{2X}{(X^2+1)^{3/2}}
]

となります。

つまりグラフの形は

[
f(X)
====

-\frac{2X}{(X^2+1)^{3/2}}
]

を描けば分かります。

---

## グラフの特徴

### 1. 原点でゼロ

[
E_x(0,0)=0
]

です。

これは、点 (x=0) では上下の負電荷からの電場が完全に打ち消し合うためです。

---

### 2. 奇関数

[
E_x(-x)
=======

# -\frac{2kq(-x)}{((-x)^2+L^2)^{3/2}}

# \frac{2kqx}{(x^2+L^2)^{3/2}}

-E_x(x)
]

したがって、

[
E_x(-x)=-E_x(x)
]

です。

つまり、グラフは原点に関して点対称です。

---

### 3. 符号

[
E_x
===

-\frac{2kqx}{(x^2+L^2)^{3/2}}
]

なので、

[
x>0 \quad \Rightarrow \quad E_x<0
]

[
x<0 \quad \Rightarrow \quad E_x>0
]

です。

つまり、右側では左向き、左側では右向きの電場になります。

これは、どちらの場合も負電荷のある中央方向へ引っ張られるような電場になっていることを表しています。

---

### 4. 無限遠ではゼロに近づく

[
|x|\to \infty
]

では分母の方が速く大きくなるので、

[
E_x \to 0
]

です。

より詳しく見ると、

[
E_x
\sim
-\frac{2kqx}{|x|^3}
]

なので、遠方では大きさがだいたい

[
\frac{1}{x^2}
]

に比例して小さくなります。

---

### 5. 最大・最小

グラフの山と谷の位置を求めます。

[
E_x(x)
======

-\frac{2kqx}{(x^2+L^2)^{3/2}}
]

を微分します。

[
\frac{dE_x}{dx}
===============

-2kq
\frac{d}{dx}
\left[
x(x^2+L^2)^{-3/2}
\right]
]

積の微分を使うと、

[
\frac{d}{dx}
\left[
x(x^2+L^2)^{-3/2}
\right]
=======

## (x^2+L^2)^{-3/2}

3x^2(x^2+L^2)^{-5/2}
]

です。

通分すると、

[
(x^2+L^2)^{-5/2}
\left[
x^2+L^2-3x^2
\right]
]

# [

(x^2+L^2)^{-5/2}
\left[
L^2-2x^2
\right]
]

したがって、

[
\frac{dE_x}{dx}
===============

-2kq
\frac{L^2-2x^2}{(x^2+L^2)^{5/2}}
]

です。

極値は

[
\frac{dE_x}{dx}=0
]

より、

[
L^2-2x^2=0
]

[
x^2=\frac{L^2}{2}
]

[
x=\pm \frac{L}{\sqrt{2}}
]

です。

---

(x=\frac{L}{\sqrt{2}}) のとき、

[
E_x
===

-\frac{2kq(L/\sqrt{2})}
{\left(L^2/2+L^2\right)^{3/2}}
]

# [

-\frac{2kqL/\sqrt{2}}
{\left(3L^2/2\right)^{3/2}}
]

計算すると、

[
E_x
===

-\frac{4kq}{3\sqrt{3}L^2}
]

です。

したがって、

[
\boxed{
x=\frac{L}{\sqrt{2}}
\text{ で最小値 }
-\frac{4kq}{3\sqrt{3}L^2}
}
]

を取ります。

同様に、

[
\boxed{
x=-\frac{L}{\sqrt{2}}
\text{ で最大値 }
\frac{4kq}{3\sqrt{3}L^2}
}
]

を取ります。

---

## グラフの概形

[
E_x(x)
]

は次のような形です。

[
\begin{array}{c|c}
x & E_x \ \hline
-\infty & 0^+ \
-\dfrac{L}{\sqrt{2}} & \dfrac{4kq}{3\sqrt{3}L^2} \
0 & 0 \
\dfrac{L}{\sqrt{2}} & -\dfrac{4kq}{3\sqrt{3}L^2} \
+\infty & 0^-
\end{array}
]

概形としては、左側に正の山、右側に負の谷を持ち、原点に関して点対称なグラフになります。

[
\boxed{
E_x(x,0)
========

-\frac{2kqx}{(x^2+L^2)^{3/2}}
}
]

---

# 問2：無限に長い線電荷が作る電場

## 設定

3次元空間で、(z) 軸上に電荷が一様に分布しています。

線密度を

[
\lambda
]

とします。

線密度とは、単位長さあたりの電荷量のことです。つまり長さ (\Delta z) の小区間に含まれる電荷は

[
\lambda \Delta z
]

です。

観測点は

[
P(a,0,0)
]

です。

問題文では対称性から、電場は (x) 成分のみを持つとされています。つまり

[
\mathbf{E}
==========

(E_x,0,0)
]

です。

ここでは (a>0) とします。

---

# 問2 (1)：微小区間の電荷 (\Delta q)

(z) 軸を微小な長さ (\Delta z) に分割します。

点

[
P_n=(0,0,z_n)
]

の付近にある微小区間の長さは

[
\Delta z
]

です。

線密度が (\lambda) なので、その微小区間に含まれる電荷は

[
\boxed{
\Delta q=\lambda \Delta z
}
]

です。

---

# 問2 (2)：(\mathbf{r}-\mathbf{r}_n) とその大きさ

観測点 (P(a,0,0)) の位置ベクトルを

[
\mathbf{r}=\overrightarrow{OP}
]

とすると、

[
\mathbf{r}=(a,0,0)
]

です。

また、点 (P_n(0,0,z_n)) の位置ベクトルを

[
\mathbf{r}_n=\overrightarrow{OP_n}
]

とすると、

[
\mathbf{r}_n=(0,0,z_n)
]

です。

したがって、

[
\mathbf{r}-\mathbf{r}_n
=======================

(a,0,0)-(0,0,z_n)
]

# [

(a,0,-z_n)
]

です。

よって、

[
\boxed{
\mathbf{r}-\mathbf{r}_n=(a,0,-z_n)
}
]

また、その大きさは

[
|\mathbf{r}-\mathbf{r}_n|
=========================

\sqrt{a^2+0^2+(-z_n)^2}
]

# [

\sqrt{a^2+z_n^2}
]

したがって、

[
\boxed{
|\mathbf{r}-\mathbf{r}_n|
=========================

\sqrt{a^2+z_n^2}
}
]

です。

---

# 問2 (3)：微小区間が作る電場の (x) 成分

微小区間の電荷を、点 (P_n) にある点電荷

[
\Delta q=\lambda\Delta z
]

とみなします。

Coulomb の法則より、

[
\Delta \mathbf{E}
=================

k\Delta q
\frac{\mathbf{r}-\mathbf{r}_n}
{|\mathbf{r}-\mathbf{r}_n|^3}
]

です。

ここに

[
\Delta q=\lambda\Delta z
]

[
\mathbf{r}-\mathbf{r}_n=(a,0,-z_n)
]

[
|\mathbf{r}-\mathbf{r}_n|
=========================

\sqrt{a^2+z_n^2}
]

を代入します。

すると、

[
\Delta \mathbf{E}
=================

k\lambda\Delta z
\frac{(a,0,-z_n)}
{\left(a^2+z_n^2\right)^{3/2}}
]

です。

したがって (x) 成分は

[
\Delta E_x
==========

k\lambda\Delta z
\frac{a}
{\left(a^2+z_n^2\right)^{3/2}}
]

つまり

[
\boxed{
\Delta E_x
==========

\frac{k\lambda a}{(a^2+z_n^2)^{3/2}}
\Delta z
}
]

です。

---

## ここでの物理的な意味

点 (P_n) 付近の電荷が作る電場には、一般には (x) 成分と (z) 成分があります。

しかし、(z=z_n) にある電荷と、(z=-z_n) にある電荷をペアで考えると、(z) 成分は互いに打ち消し合います。

一方、(x) 成分はどちらも同じ向きになります。

そのため、全体として残るのは (x) 成分だけです。

---

# 問2 (4)：全体を足し合わせて (E_x) を求める

すべての微小区間からの寄与を足し合わせると、

[
E_x
===

\sum_{n=-\infty}^{\infty}
\Delta E_x
]

です。

(3) の結果を使うと、

[
E_x
===

\sum_{n=-\infty}^{\infty}
\frac{k\lambda a}{(a^2+z_n^2)^{3/2}}
\Delta z
]

です。

(\Delta z\to 0) の極限を取ると、和は積分になります。

[
\sum_{n=-\infty}^{\infty}
f(z_n)\Delta z
\longrightarrow
\int_{-\infty}^{\infty}
f(z),dz
]

したがって、

[
E_x
===

k\lambda a
\int_{-\infty}^{\infty}
\frac{1}{(a^2+z^2)^{3/2}}
,dz
]

です。

つまり、

[
E_x
===

k\lambda a
\int_{-\infty}^{\infty}
\frac{dz}{(a^2+z^2)^{3/2}}
]

を計算すればよいことになります。

---

## 積分の計算

ヒントに従って、

[
z=a\tan\theta
]

と置きます。

このとき、

[
dz=a\sec^2\theta,d\theta
]

です。

また、

[
a^2+z^2
=======

a^2+a^2\tan^2\theta
]

# [

a^2(1+\tan^2\theta)
]

ここで、

[
1+\tan^2\theta=\sec^2\theta
]

なので、

[
a^2+z^2
=======

a^2\sec^2\theta
]

したがって、

[
(a^2+z^2)^{3/2}
===============

(a^2\sec^2\theta)^{3/2}
]

# [

a^3\sec^3\theta
]

です。

---

積分範囲も変換します。

[
z\to -\infty
]

のとき、

[
a\tan\theta\to -\infty
]

なので、

[
\theta\to -\frac{\pi}{2}
]

です。

また、

[
z\to +\infty
]

のとき、

[
\theta\to \frac{\pi}{2}
]

です。

したがって、

[
\int_{-\infty}^{\infty}
\frac{dz}{(a^2+z^2)^{3/2}}
]

は

[
\int_{-\pi/2}^{\pi/2}
\frac{a\sec^2\theta,d\theta}
{a^3\sec^3\theta}
]

になります。

整理すると、

# [

\frac{1}{a^2}
\int_{-\pi/2}^{\pi/2}
\frac{\sec^2\theta}{\sec^3\theta}
,d\theta
]

# [

\frac{1}{a^2}
\int_{-\pi/2}^{\pi/2}
\frac{1}{\sec\theta}
,d\theta
]

# [

\frac{1}{a^2}
\int_{-\pi/2}^{\pi/2}
\cos\theta
,d\theta
]

です。

これを計算すると、

[
\frac{1}{a^2}
\int_{-\pi/2}^{\pi/2}
\cos\theta
,d\theta
========

\frac{1}{a^2}
\left[
\sin\theta
\right]_{-\pi/2}^{\pi/2}
]

# [

\frac{1}{a^2}
\left(
\sin\frac{\pi}{2}
-----------------

\sin\left(-\frac{\pi}{2}\right)
\right)
]

# [

\frac{1}{a^2}(1-(-1))
]

# [

\frac{2}{a^2}
]

です。

したがって、

[
\int_{-\infty}^{\infty}
\frac{dz}{(a^2+z^2)^{3/2}}
==========================

\frac{2}{a^2}
]

です。

---

これを

[
E_x
===

k\lambda a
\int_{-\infty}^{\infty}
\frac{dz}{(a^2+z^2)^{3/2}}
]

に代入すると、

[
E_x
===

k\lambda a
\cdot
\frac{2}{a^2}
]

# [

\frac{2k\lambda}{a}
]

したがって、

[
\boxed{
E_x
===

\frac{2k\lambda}{a}
}
]

です。

よって電場ベクトルは

[
\boxed{
\mathbf{E}
==========

\left(
\frac{2k\lambda}{a},
0,
0
\right)
}
]

です。

---

## 向きについて

(\lambda>0) のとき、線電荷は正電荷なので、電場は線電荷から外向きになります。

点 (P(a,0,0)) は (z) 軸から見て (+x) 方向にあるので、

[
\lambda>0
]

なら

[
\mathbf{E}
==========

\left(
\frac{2k\lambda}{a},0,0
\right)
]

は (+x) 方向です。

一方、

[
\lambda<0
]

なら、電場は線電荷に向かうので、(-x) 方向になります。

式

[
E_x=\frac{2k\lambda}{a}
]

は、(\lambda) の符号まで含めて向きを表しています。

---

# 最終答えまとめ

## 問1

[
\boxed{
\mathbf{E}(x,0)
===============

\left(
-\frac{2kqx}{(x^2+L^2)^{3/2}},
0
\right)
}
]

グラフは

[
\boxed{
E_x(x,0)
========

-\frac{2kqx}{(x^2+L^2)^{3/2}}
}
]

であり、原点に関して点対称、(x>0) で負、(x<0) で正です。

極値は

[
\boxed{
x=-\frac{L}{\sqrt{2}}
\text{ で }
E_x=\frac{4kq}{3\sqrt{3}L^2}
}
]

[
\boxed{
x=\frac{L}{\sqrt{2}}
\text{ で }
E_x=-\frac{4kq}{3\sqrt{3}L^2}
}
]

です。

---

## 問2

[
\boxed{
\Delta q=\lambda\Delta z
}
]

[
\boxed{
\mathbf{r}-\mathbf{r}_n=(a,0,-z_n)
}
]

[
\boxed{
|\mathbf{r}-\mathbf{r}_n|=\sqrt{a^2+z_n^2}
}
]

[
\boxed{
\Delta E_x
==========

\frac{k\lambda a}{(a^2+z_n^2)^{3/2}}\Delta z
}
]

[
\boxed{
E_x
===

k\lambda a
\int_{-\infty}^{\infty}
\frac{dz}{(a^2+z^2)^{3/2}}
}
]

[
\boxed{
E_x=\frac{2k\lambda}{a}
}
]

したがって、

[
\boxed{
\mathbf{E}
==========

\left(
\frac{2k\lambda}{a},0,0
\right)
}
]
