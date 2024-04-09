**本文为转载，为的是有些时候上不了洛谷，转载自：https://www.luogu.com.cn/blog/IowaBattleship/latex-gong-shi-tai-quan**  
-----------
有些似乎在这里程显不出来，请见谅
------------

### 数学公式的插入

将数学公式写在 `$ $` 之间，代表的是插入行内数学公式（通常称为行内模式）。  
将数学公式写在 `$$ $$` 之间，会使公式独立成一行并强制居中（通常称为独立模式）。

------------

### 声调 / 变音符号  

```markdown
$\dot{a} \ddot{a} \acute{a} \grave{a}$
```

$\quad\dot{a}\quad\ddot{a}\quad\acute{a}\quad\grave{a}$

```markdown
$\check{a} \breve{a} \tilde{a} \bar{a}$
```

$\quad\check{a}\quad\breve{a}\quad\tilde{a}\quad\bar{a}$

```markdown
$\hat{a} \widehat{a} \vec{a}$
```

$\quad\hat{a}\quad\widehat{a}\quad\vec{a}$

------------

### 标准函数

```markdown
$\exp_a b=a^b \exp b=e^b 10^m$
```

$\quad\exp_a b=a^b\quad\exp b=e^b\quad10^m$

```markdown
$\sin a \cos b \tan c \sec d \csc e \cot f$
```

$\quad\sin a\quad\cos b\quad\tan c\quad\sec d\quad\csc e\quad\cot f$

```markdown
$\arcsin a \arccos b \arctan c$
```

$\quad\arcsin a\quad\arccos b\quad\arctan c$

```markdown
$\sinh a \cosh b \tanh c \coth d$
```

$\quad\sinh a\quad\cosh b\quad\tanh c\quad\coth d$

```markdown
$\sh a \ch b \th c$
```

$\quad\sh a\quad\ch b\quad\th c$

```markdown
$\operatorname{argsh} a \operatorname{argch} b \operatorname{argth} c$
```

PS：`\operatorname{}` 貌似可以将任何字符转换成标准函数的形式。

$\quad\operatorname{argsh} a\quad\operatorname{argch} b\quad\operatorname{argth} c$

```markdown
$\left\vert a\right\vert \min(x,y) \max(x,y)$
```

$\quad\left\vert a\right\vert\quad\min(x,y)\quad\max(x,y)$

------------

### 界限

```markdown
$\min x \max y \inf s \sup t$
```

$\quad\min x\quad\max y\quad\inf s\quad\sup t$

```markdown
$\lim u \liminf v \limsup w$
```

$\quad\lim u\quad\liminf v\quad\limsup w$

```markdown
$\dim p \deg q \det m \ker\phi$
```

$\quad\dim p\quad\deg q\quad\det m\quad\ker\phi$

------------

### 投射

PS：感觉这翻译很奇怪，应该是映射吧。

```markdown
$\Pr j \hom l \lVert z\rVert \arg z$
```

PS：个人认为 `\lVert`、`\rVert` 与 `\Vert` 和 `\|` 并没有什么区别。

$\quad\Pr j\quad\hom l\quad\lVert z\rVert\quad\arg z$  

------------

### 微分及导数

```markdown
$dt \mathrm{d}t \partial t \nabla\psi$
```

$\quad dt\quad\mathrm{d}t\quad\partial t\quad\nabla\psi$

```markdown
$\prime \backprime f^\prime f' f'' f^{(3)} \dot{y} \ddot{y}$
```

$\quad\prime\quad\backprime\quad f^\prime\quad f'\quad f''\quad f^{(3)}\quad\dot{y}\quad\ddot{y}$

------------

### 类字母符号及常数

```markdown
$\infty \aleph \complement \backepsilon \eth \Finv \hbar$
```

$\quad\infty\quad\aleph\quad\complement\quad\backepsilon\quad\eth\quad\Finv\quad\hbar$

```markdown
$\Im \imath \jmath \Bbbk \ell \mho \wp \Re \circledS$
```

$\quad\Im\quad\imath\quad\jmath\quad\Bbbk\quad\ell\quad\mho\quad\wp\quad\Re\quad\circledS$

------------

### 模算数

```markdown
$a\equiv1\pmod{m}$
```

$\quad a\equiv1\pmod{m}$

```markdown
$a\bmod b$
```

$\quad a\bmod b$

```markdown
$\gcd(m,n) \operatorname{lcm}(m,n)$
```

$\quad\gcd(m,n)\quad\operatorname{lcm}(m,n)$

```markdown
$\mid \nmid \shortmid \nshortmid$
```

PS：`\mid` 可以用 `|` 代替。（管理员注：`\mid` 实际上差不多是 `\mathrel{|}`，两侧的 spacing 有区别的）

$\quad\mid\quad\nmid\quad\shortmid\quad\nshortmid$

```markdown
$a\%b$
```

$\quad a\%b$

（管理员注：不建议在公式中使用 `\%` 作为取模，一般仅作百分号使用）

------------

### 根号

```markdown
$\surd \sqrt{2} \sqrt[n]{} \sqrt[n]{x}$
```

$\quad\surd\quad\sqrt{2}\quad\sqrt[n]{}\quad\sqrt[n]{x}$  

------------

### 运算符

```markdown
$+ - \pm \mp \dotplus$
```

$\quad+\quad-\quad\pm\quad\mp\quad\dotplus$

```markdown
$\times \div \divideontimes / \backslash$
```

$\quad\times\quad\div\quad\divideontimes\quad/\quad\backslash$

```markdown
$\cdot * \star \circ \bullet$
```

PS：`*` 可以用 `\ast` 代替。

$\quad\cdot\quad*\quad\star\quad\circ\quad\bullet$

```markdown
$\boxplus \boxminus \boxtimes \boxdot$
```

$\quad\boxplus\quad\boxminus\quad\boxtimes\quad\boxdot$

```markdown
$\oplus \ominus \otimes \oslash \odot$
```

$\quad\oplus\quad\ominus\quad\otimes\quad\oslash\quad\odot$

```markdown
$\circleddash \circledcirc \circledast$
```

$\quad\circleddash\quad\circledcirc\quad\circledast$

```markdown
$\bigoplus \bigotimes \bigodot$
```

$\quad\bigoplus\quad\bigotimes\quad\bigodot$

------------

### 集合

```markdown
$\{ \} \emptyset \varnothing$
```

$\quad\{\quad\}\quad\emptyset\quad\varnothing$

```markdown
$\in \notin \not\in \ni \not\ni$
```

PS：`\not` 是在下一个字符上画斜杠。

$\quad\in\quad\notin\quad\not\in\quad\ni\quad\not\ni$

```markdown
$\cap \Cap \sqcap \bigcap$
```

$\quad\cap\quad\Cap\quad\sqcap\quad\bigcap$

```markdown
$\cup \Cup \sqcup \bigcup \bigsqcup \uplus \biguplus$
```

$\quad\cup\quad\Cup\quad\sqcup\quad\bigcup\quad\bigsqcup\quad\uplus\quad\biguplus$

```markdown
$\setminus \smallsetminus \times$
```

$\quad\setminus\quad\smallsetminus\quad\times$

```markdown
$\subset \Subset \sqsubset$
```

$\quad\subset\quad\Subset\quad\sqsubset$

```markdown
$\supset \Supset \sqsupset$
```

$\quad\supset\quad\Supset\quad\sqsupset$

```markdown
$\subseteq \nsubseteq \subsetneq \varsubsetneq \sqsubseteq$
```

$\quad\subseteq\quad\nsubseteq\quad\subsetneq\quad\varsubsetneq\quad\sqsubseteq$

```markdown
$\supseteq \nsupseteq \supsetneq \varsupsetneq \sqsupseteq$
```

$\quad\supseteq\quad\nsupseteq\quad\supsetneq\quad\varsupsetneq\quad\sqsupseteq$

```markdown
$\subseteqq \nsubseteqq \subsetneqq \varsubsetneqq$
```

$\quad\subseteqq\quad\nsubseteqq\quad\subsetneqq\quad\varsubsetneqq$

```markdown
$\supseteqq \nsupseteqq \supsetneqq \varsupsetneqq$
```

$\quad\supseteqq\quad\nsupseteqq\quad\supsetneqq\quad\varsupsetneqq$

------------

### 关系符号  

```markdown
$= \ne \neq \equiv \not\equiv$
```

PS：表示并没有看出来 `\ne` 和 `\neq` 的区别……（管理员注：因为是一样的）

$\quad=\quad\ne\quad\neq\quad\equiv\quad\not\equiv$

```markdown
$\doteq \doteqdot \overset{\underset{def}{}}{=} :=$
```

$\quad\doteq\quad\doteqdot\quad\overset{\underset{def}{}}{=}\quad:=$

```markdown
$\sim \nsim \backsim \thicksim \simeq \backsimeq \eqsim \cong \ncong$
```

$\quad\sim\quad\nsim\quad\backsim\quad\thicksim\quad\simeq\quad\backsimeq\quad\eqsim\quad\cong\quad\ncong$

```markdown
$\approx \thickapprox \approxeq \asymp \propto \varpropto$
```

$\quad\approx\quad\thickapprox\quad\approxeq\quad\asymp\quad\propto\quad\varpropto$

```markdown
$< \nless \ll \not\ll \lll \not\lll \lessdot$
```

$\quad<\quad\nless\quad\ll\quad \not\ll\quad\lll\quad \not\lll\quad\lessdot$

```markdown
$> \ngtr \gg \not\gg \ggg \not\ggg \gtrdot$
```

$\quad>\quad\ngtr\quad\gg\quad \not\gg\quad\ggg\quad \not\ggg\quad\gtrdot$

```markdown
$\le \leq \lneq \leqq \nleq \nleqq \lneqq \lvertneqq$
```

$\quad\le\quad\leq\quad\lneq\quad\leqq\quad\nleq\quad\nleqq\quad\lneqq\quad\lvertneqq$

```markdown
$\ge \geq \gneq \geqq \ngeq \ngeqq \gneqq \gvertneqq$
```

$\quad\ge\quad\geq\quad\gneq\quad\geqq\quad\ngeq\quad\ngeqq\quad\gneqq\quad\gvertneqq$

```markdown
$\lessgtr \lesseqgtr \lesseqqgtr \gtrless \gtreqless \gtreqqless$
```

$\quad\lessgtr\quad\lesseqgtr\quad\lesseqqgtr\quad\gtrless\quad\gtreqless\quad\gtreqqless$

```markdown
$\leqslant \nleqslant \eqslantless$
```

$\quad\leqslant\quad\nleqslant\quad\eqslantless$

```markdown
$\geqslant \ngeqslant \eqslantgtr$
```

$\quad\geqslant\quad\ngeqslant\quad\eqslantgtr$

```markdown
$\lesssim \lnsim \lessapprox \lnapprox$
```

$\quad\lesssim\quad\lnsim\quad\lessapprox\quad\lnapprox$

```markdown
$\gtrsim \gnsim \gtrapprox \gnapprox$
```

$\quad\gtrsim\quad\gnsim\quad\gtrapprox\quad\gnapprox$

```markdown
$\prec \nprec \preceq \npreceq \precneqq$
```

$\quad\prec\quad\nprec\quad\preceq\quad\npreceq\quad\precneqq$

```markdown
$\succ \nsucc \succeq \nsucceq \succneqq$
```

$\quad\succ\quad\nsucc\quad\succeq\quad\nsucceq\quad\succneqq$

```markdown
$\preccurlyeq \curlyeqprec$
```

$\quad\preccurlyeq\quad\curlyeqprec$

```markdown
$\succcurlyeq \curlyeqsucc$
```

$\quad\succcurlyeq\quad\curlyeqsucc$

```markdown
$\precsim \precnsim \precapprox \precnapprox$
```

$\quad\precsim\quad\precnsim\quad\precapprox\quad\precnapprox$

```markdown
$\succsim \succnsim \succapprox \succnapprox$
```

$\quad\succsim\quad\succnsim\quad\succapprox\quad\succnapprox$

------------

### 几何符号  
```cpp
$\parallel \nparallel \shortparallel \nshortparallel$
 ps:\parallel应该和\|是一样的。
```
$\quad\parallel\quad\nparallel\quad\shortparallel\quad\nshortparallel$  
```cpp
$\perp \angle \sphericalangle \measuredangle 45^\circ$
```
$\quad\perp\quad\angle\quad\sphericalangle\quad\measuredangle\quad45^\circ$  
```cpp
$\Box \blacksquare \diamond \Diamond \lozenge \blacklozenge \bigstar$
```
$\quad\Box\quad\blacksquare\quad\diamond\quad\Diamond\quad\lozenge\quad\blacklozenge\quad\bigstar$  
```cpp
$\bigcirc \triangle \bigtriangleup \bigtriangledown$
 ps:并没有看出\triangle和\bigtriangleup有什么区别。
```
$\quad\bigcirc\quad\triangle\quad\bigtriangleup\quad\bigtriangledown$  
```cpp
$\vartriangle \triangledown \triangleleft \triangleright$
```
$\quad\vartriangle\quad\triangledown\quad\triangleleft\quad\triangleright$  
```cpp
$\blacktriangle \blacktriangledown \blacktriangleleft \blacktriangleright$
```
$\quad\blacktriangle\quad\blacktriangledown\quad\blacktriangleleft\quad\blacktriangleright$  

------------

### 逻辑符号  
```cpp
$\forall \exists \nexists$
```
$\quad\forall\quad\exists\quad\nexists$  
```cpp
$\therefore \because \And$
 ps:\And也可用\&，至少我没看出来这两个有什么差别。
```
$\quad\therefore\quad\because\quad\And$  
```cpp
$\lor \vee \curlyvee \bigvee$
```
$\quad\lor\quad\vee\quad\curlyvee\quad\bigvee$  
```cpp
$\land \wedge \curlywedge \bigwedge$
```
$\quad\land\quad\wedge\quad\curlywedge\quad\bigwedge$  
```cpp
$\bar{q} \bar{abc} \overline{q} \overline{abc}$
```
$\quad\bar{q}\quad\bar{abc}\quad\overline{q}\quad\overline{abc}$  
```cpp
$\lnot \neg \bot \top$
```
$\quad\lnot\quad\neg\quad\bot\quad\top$  
```cpp
$\vdash \dashv \vDash \Vdash \models$
```
$\quad\vdash\quad\dashv\quad\vDash\quad\Vdash\quad\models$  
```cpp
$\Vvdash \nvdash \nVdash \nvDash \nVDash$
```
$\quad\Vvdash\quad\nvdash\quad\nVdash\quad\nvDash\quad\nVDash$  
```cpp
$\ulcorner \urcorner \llcorner \lrcorner$
```
$\quad\ulcorner\quad\urcorner\quad\llcorner\quad\lrcorner$  

------------

### 箭头  
```cpp
$\Rrightarrow \Lleftarrow$
```
$\quad\Rrightarrow\quad\Lleftarrow$  
```cpp
$\Rightarrow \nRightarrow \Longrightarrow \implies$
```
$\quad\Rightarrow\quad\nRightarrow\quad\Longrightarrow\quad\implies$  
```cpp
$\Leftarrow \nLeftarrow \Longleftarrow$
```
$\quad\Leftarrow\quad\nLeftarrow\quad\Longleftarrow$  
```cpp
$\Leftrightarrow \nLeftrightarrow \Longleftrightarrow \iff$
```
$\quad\Leftrightarrow\quad\nLeftrightarrow\quad\Longleftrightarrow\quad\iff$  
```cpp
$\Uparrow \Downarrow \Updownarrow$
```
$\quad\Uparrow\quad\Downarrow\quad\Updownarrow$  
```cpp
$\leftarrow \rightarrow \nleftarrow \nrightarrow \leftrightarrow \nleftrightarrow \longleftarrow \longrightarrow \longleftrightarrow$
 ps:\leftarrow可用\gets代替，\rightarrow可用\to代替。
```
$\quad\leftarrow\quad\rightarrow\quad\nleftarrow\quad\nrightarrow\quad\leftrightarrow\quad\nleftrightarrow\quad\longleftarrow\quad\longrightarrow\quad\longleftrightarrow$  
```cpp
$\uparrow \downarrow \updownarrow \nearrow \searrow \nwarrow \swarrow$
```
$\quad\uparrow\quad\downarrow\quad\updownarrow\quad\nearrow\quad\searrow\quad\nwarrow\quad\swarrow$  
```cpp
$\mapsto \longmapsto$
```
$\quad\mapsto\quad\longmapsto$  
```cpp
$\rightharpoonup \rightharpoondown \leftharpoonup \leftharpoondown \upharpoonleft \upharpoonright \downharpoonleft \downharpoonright \leftrightharpoons \rightleftharpoons$
```
$\quad\rightharpoonup\quad\rightharpoondown\quad\leftharpoonup\quad\leftharpoondown\quad\upharpoonleft\quad\upharpoonright\quad\downharpoonleft\quad\downharpoonright\quad\leftrightharpoons\quad\rightleftharpoons$  
```cpp
$\curvearrowleft \circlearrowleft \Lsh \upuparrows \rightrightarrows \rightleftarrows \rightarrowtail \looparrowright$
```
$\quad\curvearrowleft\quad\circlearrowleft\quad\Lsh\quad\upuparrows\quad\rightrightarrows\quad\rightleftarrows\quad\rightarrowtail\quad\looparrowright$  
```cpp
$\curvearrowright \circlearrowright \Rsh \downdownarrows \leftleftarrows \leftrightarrows \leftarrowtail \looparrowleft$
```
$\quad\curvearrowright\quad\circlearrowright\quad\Rsh\quad\downdownarrows\quad\leftleftarrows\quad\leftrightarrows\quad\leftarrowtail\quad\looparrowleft$  
```cpp
$\hookrightarrow \hookleftarrow \multimap \leftrightsquigarrow \rightsquigarrow \twoheadrightarrow \twoheadleftarrow$
```
$\quad\hookrightarrow\quad\hookleftarrow\quad\multimap\quad\leftrightsquigarrow\quad\rightsquigarrow\quad\twoheadrightarrow\quad\twoheadleftarrow$  
```cpp
$\xleftarrow{left} \xrightarrow{right} \xLeftarrow{Left} \xRightarrow{Right} \xleftrightarrow{left\& right} \xLeftrightarrow{Left\& Right}$
```
$\quad\xleftarrow{left}\quad \xrightarrow{right} \quad \xLeftarrow{Left} \quad \xRightarrow{Right} \quad \xleftrightarrow{left\& right} \quad \xLeftrightarrow{Left\& Right}$  

------------

### 特殊符号  
```cpp
$\amalg \% \dagger \ddagger \ldots \cdots$
 ps:\dots和\ldots貌似是一样的。
```
$\quad\amalg\quad\%\quad\dagger\quad\ddagger\quad\ldots\quad\cdots$  
```cpp
$\smile \frown \wr$
```
$\quad\smile\quad\frown\quad\wr$  
```cpp
$\diamondsuit \heartsuit \clubsuit \spadesuit \Game \flat \natural \sharp$
```
$\quad\diamondsuit\quad\heartsuit\quad\clubsuit\quad\spadesuit\quad\Game\quad\flat\quad\natural\quad\sharp$  
  
以下是$Wiki$中没有分类的符号，我暂且将其归入特殊符号中  
```cpp
$\diagup \diagdown \centerdot \ltimes \rtimes \leftthreetimes \rightthreetimes$
```
$\quad\diagup\quad\diagdown\quad\centerdot\quad\ltimes\quad\rtimes\quad\leftthreetimes\quad\rightthreetimes$  
```cpp
$\eqcirc \circeq \triangleq \bumpeq \Bumpeq \doteqdot \risingdotseq \fallingdotseq$
```
$\quad\eqcirc\quad\circeq\quad\triangleq\quad\bumpeq\quad\Bumpeq\quad\doteqdot\quad\risingdotseq\quad\fallingdotseq$  
```cpp
$\intercal \barwedge \veebar \doublebarwedge \between \pitchfork$
```
$\quad\intercal\quad\barwedge\quad\veebar\quad\doublebarwedge\quad\between\quad\pitchfork$  
```cpp
$\vartriangleleft \ntriangleleft \vartriangleright \ntriangleright$
```
$\quad\vartriangleleft\quad\ntriangleleft\quad\vartriangleright\quad\ntriangleright$  
```cpp
$\trianglelefteq \ntrianglelefteq \trianglerighteq \ntrianglerighteq$
```
$\quad\trianglelefteq\quad\ntrianglelefteq\quad\trianglerighteq\quad\ntrianglerighteq$  
```cpp
$\LaTeX$

 ps:应评论要求加上，其实介于阅读体验还是少用些。
```
$\quad\LaTeX$

------------

### 上标、下标及积分等  
#### 上标  
```cpp
$a^2$
```
$\quad a^2$  
#### 下标  
```cpp
$a_2$
```
$\quad a_2$  
#### 组合  
```cpp
$a^{2+2} a_{i,j}$
```
$\quad a^{2+2}\quad a_{i,j}$  
#### 结合上下标  
```cpp
$a^2_2$
```
$\quad a^2_2$  
#### 前置上下标  
```cpp
${}^2_1\!X^3_4$
 ps:\!的作用在下面空格一栏有讲述。
```
$\quad {}^2_1\!X^3_4$  
#### 导数  
```cpp
$ (HTML)x' (PNG)x^\prime (错误)x\prime$
```
$\quad x'\quad x^\prime\quad x\prime$  
#### 导数点  
```cpp
$\dot{x} \ddot{x}$
```
$\quad\dot{x}\quad\ddot{x}$  
#### 向量  
```cpp
$\vec{x} \overleftarrow{AB} \overrightarrow{AB} \widehat{AB}$
```
$\quad\vec{a}\quad\overleftarrow{AB}\quad\overrightarrow{AB}\quad\widehat{AB}$  
#### 上弧  
```cpp
$\overset{\frown}{AB}$
 ps:正确的语法应该是\overarc，但因为没有引入amsmath宏包，所以无法使用，只能用这个替代下。
```
$\quad\overset{\frown}{AB}$  
#### 上划线
```cpp
$\overline{ABC}$
```
$\quad\overline{ABC}$  
#### 下划线  
```cpp
$\underline{ABC}$
```
$\quad\underline{ABC}$  
#### 上括号  
```cpp
$\overbrace{1+2+\cdots+100}$  

$\begin{matrix}5050\\\overbrace{1+2+\cdots+100}\end{matrix}$  
 ps:'\\'是换行的意思。
```
$\quad\overbrace{1+2+\cdots+100}$  

$\quad\begin{matrix}5050\\\overbrace{1+2+\cdots+100}\end{matrix}$  
#### 下括号  
```cpp
$\underbrace{1+2+\cdots+100}$  

$\begin{matrix}\underbrace{1+2+\cdots+100}\\5050\end{matrix}$
```
$\quad\underbrace{1+2+\cdots+100}$  

$\quad\begin{matrix}\underbrace{1+2+\cdots+100}\\5050\end{matrix}$  
#### 求和  
```cpp
$\sum_{i=1}^na_i \sum\limits_{i=1}^na_i$
```
$\quad\sum_{i=1}^na_i\quad\sum\limits_{i=1}^na_i$  
#### 求积  
```cpp
$\prod_{i=1}^na_i \prod\limits_{i=1}^na_i$
```
$\quad\prod_{i=1}^na_i\quad\prod\limits_{i=1}^na_i$  
#### 上积  
```cpp
$\coprod_{i=1}^na_i \coprod\limits_{i=1}^na_i$
```
$\quad\coprod_{i=1}^na_i\quad\coprod\limits_{i=1}^na_i$  
#### 极限  
```cpp
$\lim_{n\to\infty}x_n \lim\limits_{n\to\infty}x_n$
```
$\quad\lim_{n\to\infty}x_n\quad\lim\limits_{n\to\infty}x_n$  
#### 积分  
```cpp
$\int_{-N}^{N}e^x\,dx$
 ps:\,的作用在下面空格一栏有讲。
```
$\quad\int_{-N}^{N}e^x\,dx$  
#### 双重积分  
```cpp
$\iint_M^Ndx\,dy$
```
$\quad\iint_M^Ndx\,dy$  
#### 三重积分  
```cpp
$\iiint_M^Ndx\,dy\,dz$
```
$\quad\iiint_M^Ndx\,dy\,dz$  
#### 闭合的曲线、曲面积分  
```cpp
$\oint_Cx^3\,dx+4y^2\,dy$
```
$\quad\oint_Cx^3\,dx+4y^2\,dy$  
#### 交集  
```cpp
$\bigcap_1^np \bigcap\limits_1^np$
```
$\quad\bigcap_1^np\quad\bigcap\limits_1^np$  
#### 并集  
```cpp
$\bigcup_1^np \bigcup\limits_1^np$
```
$\quad\bigcup_1^np\quad\bigcup\limits_1^np$  

------------

### 分数、矩阵等  

#### 分数  
```cpp
$\frac{1}{2}=0.5$
```
$\quad\frac{1}{2}=0.5$  
#### 小型分数  
```cpp
$\tfrac{1}{2}=0.5$
 ps:并不清楚为什么洛谷的LaTeX里普通分数和小型分数一样大……
```
$\quad\tfrac{1}{2}=0.5$  
#### 大型分数  
```cpp
$\dfrac{1}{2}=0.5 \dfrac{1}{x+\dfrac{3}{y+\dfrac{1}{5}}}$
```
$\quad\dfrac{1}{2}=0.5\qquad\dfrac{1}{x+\dfrac{3}{y+\dfrac{1}{5}}}$  
#### 二项式系数  
```cpp
$\dbinom{n}{m}=\dbinom{n}{n-m}=C_n^m=C_n^{n-m}$
```
$\quad\dbinom{n}{m}=\dbinom{n}{n-m}=C_n^m=C_n^{n-m}$  
#### 小型二项式系数  
```cpp
$\tbinom{n}{m}=\tbinom{n}{n-m}=C_n^m=C_n^{n-m}$
```
$\quad\tbinom{n}{m}=\tbinom{n}{n-m}=C_n^m=C_n^{n-m}$  
```cpp
$\binom{n}{m}=\binom{n}{n-m}=C_n^m=C_n^{n-m}$
```
$\quad\binom{n}{m}=\binom{n}{n-m}=C_n^m=C_n^{n-m}$  
#### 矩阵  
```cpp
$\begin{matrix}a&b\\c&d\end{matrix}$
 ps:&是使上下行对齐。
```
$\quad\begin{matrix}a&b\\c&d\end{matrix}$  
```cpp
$\begin{vmatrix}a&b\\c&d\end{vmatrix}$
```
$\quad\begin{vmatrix}a&b\\c&d\end{vmatrix}$  
```cpp
$\begin{Vmatrix}a&b\\c&d\end{Vmatrix}$
```
$\quad\begin{Vmatrix}a&b\\c&d\end{Vmatrix}$  
```cpp
$\begin{bmatrix}a&\cdots&b\\\vdots&\ddots&\vdots\\c&\cdots&d\end{bmatrix}$
 ps:\vdots是竖着3个点，\ddots是斜着3个点。
```
$\quad\begin{bmatrix}a&\cdots&b\\\vdots&\ddots&\vdots\\c&\cdots&d\end{bmatrix}$  
```cpp
$\begin{Bmatrix}a&c\\b&d\end{Bmatrix}$
```
$\quad\begin{Bmatrix}a&c\\b&d\end{Bmatrix}$  
```cpp
$\begin{pmatrix}a&c\\b&d\end{pmatrix}$
```
$\quad\begin{pmatrix}a&c\\b&d\end{pmatrix}$  

#### 矩阵嵌套
```cpp
$\begin{vmatrix} \begin{Bmatrix}A & \\ c & d \end{Bmatrix} & x\\ \dfrac{1}{2} & \begin{matrix} 1 & 2 \\ 3 & 4 \end{matrix} \end{vmatrix}$ 
```
$\quad \begin{vmatrix} \begin{Bmatrix}A & \\ c & d \end{Bmatrix} & x\\ \dfrac{1}{2} & \begin{matrix} 1 & 2 \\ 3 & 4 \end{matrix} \end{vmatrix}$  

#### 条件定义(如分段函数)  
```cpp
$f(x)=\begin{cases}x-1&x\leqslant3\\x^2+3x-1&x>3\end{cases}$
```
$\quad f(x)=\begin{cases}x-1&x\leqslant3\\x^2+3x-1&x>3\end{cases}$  
#### 方程组  
```cpp
$\begin{cases}2x+9y-5z=10\\4x+20y+z=24\\x-\dfrac{1}{2}y+3z=8\end{cases}$
```
$\quad\begin{cases}2x+9y-5z=10\\4x+20y+z=24\\x-\dfrac{1}{2}y+3z=8\end{cases}$  

#### 多行等式
```cpp
$\begin{aligned}f(x) & = (x + 1)^2 \\ & = x^2 + 2x + 1\end{aligned}$

$\begin{aligned}a_1 & = 1 \\ a_2 & = 2 \\ & \dots \\ a_n & = n\end{aligned}$ 

 ps:原语法为align，现在是aligned。
```

$\quad\begin{aligned}f(x) & = (x + 1)^2 \\ & = x^2 + 2x + 1\end{aligned}\qquad\begin{aligned}a_1 & = 1 \\ a_2 & = 2 \\ & \dots \\ a_n & = n\end{aligned}$  

#### 数组/表格  
```cpp
$\begin{array}{|c|c||c|}x&y&z\\8&2&4\\2&3&9\\10&\dfrac{3}{4}&\sqrt{3}\\a&b&c\end{array}$
 ps:\begin{array}{}←这个大括号里是形如'|c|c||c|'这样的格式，'|'是两列的分割线，'c'是表示这里有一列，而内容中使用'&'来分开每一列的内容。这里可能讲的不是很清楚，所以最好还是自己尝试一下。
```
$\quad\begin{array}{|c|c||c|}x&y&z\\8&2&4\\2&3&9\\10&\dfrac{3}{4}&\sqrt{3}\\a&b&c\end{array}$  

------------

### 字体  
#### 希腊字母  
貌似洛谷对一些希腊字母不支持，也许是因为像英文字母，所以我这里只好用英文字母代替了。  
```cpp
$A B\Gamma\Delta EZH\Theta$
```
$\quad A B\Gamma\Delta EZH\Theta$  
```cpp
$IK\Lambda MN\Xi O\Pi$
```
$\quad IK\Lambda MN\Xi O\Pi$  
```cpp
$P\Sigma T\Upsilon\Phi X\Psi\Omega$
```
$\quad P\Sigma T\Upsilon\Phi X\Psi\Omega$  
```cpp
$\alpha\beta\gamma\delta\epsilon\zeta\eta\theta$
```
$\quad\alpha\beta\gamma\delta\epsilon\zeta\eta\theta$  
```cpp
$\iota\kappa\lambda\mu\nu\xi\omicron\pi$
```
$\quad\iota\kappa\lambda\mu\nu\xi\omicron\pi$  
```cpp
$\rho\sigma\tau\upsilon\phi\chi\psi\omega$
```
$\quad\rho\sigma\tau\upsilon\phi\chi\psi\omega$  
```cpp
$\varepsilon\digamma\varkappa\varpi$
```
$\quad\varepsilon\digamma\varkappa\varpi$  
```cpp
$\varrho\varsigma\vartheta\varphi$
```
$\quad\varrho\varsigma\vartheta\varphi$  
#### 希伯来符号  
```cpp
$\aleph\beth\gimel\daleth$
```
$\quad\aleph\beth\gimel\daleth$  
#### 黑板粗体  
```cpp
$\mathbb{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$
 ps:仅支持大写英文字母。
```
$\quad\mathbb{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
#### 粗体  
```cpp
$\mathbf{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\mathbf{abcdefghijklmnopqrstuvwxyz}$
$\mathbf{0123456789}$
 ps:支持大小写英文字母、数字和大写希腊字母。
```
$\quad\mathbf{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\quad\mathbf{abcdefghijklmnopqrstuvwxyz}$  
$\quad\mathbf{A B\Gamma\Delta EZH\Theta}$  
$\quad\mathbf{IK\Lambda MN\Xi O\Pi}$  
$\quad\mathbf{P\Sigma T\Upsilon\Phi X\Psi\Omega}$  
$\quad\mathbf{0123456789}$  
#### 斜体(英文字母和小写希腊字母默认)  
```cpp
$\mathit{A B\Gamma\Delta EZH\Theta}$  
$\mathit{IK\Lambda MN\Xi O\Pi}$  
$\mathit{P\Sigma T\Upsilon\Phi X\Psi\Omega}$  
$\mathit{0123456789}$  
```
$\quad\mathit{A B\Gamma\Delta EZH\Theta}$  
$\quad\mathit{IK\Lambda MN\Xi O\Pi}$  
$\quad\mathit{P\Sigma T\Upsilon\Phi X\Psi\Omega}$  
$\quad\mathit{0123456789}$  
#### 罗马体  
```cpp
$\mathrm{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\mathrm{abcdefghijklmnopqrstuvwxyz}$  
$\mathrm{0123456789}$
 ps:支持大小写英文字母和数字。
```
$\quad\mathrm{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\quad\mathrm{abcdefghijklmnopqrstuvwxyz}$  
$\quad\mathrm{0123456789}$  
#### 打字机字体
```cpp
$\mathtt{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\mathtt{abcdefghijklmnopqrstuvwxyz}$  
$\mathtt{A B\Gamma\Delta EZH\Theta}$  
$\mathtt{IK\Lambda MN\Xi O\Pi}$  
$\mathtt{P\Sigma T\Upsilon\Phi X\Psi\Omega}$  
$\mathtt{0123456789}$  
 ps:支持大小写英文字母、大写希腊字母和数字。
```
$\quad \mathtt{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\quad \mathtt{abcdefghijklmnopqrstuvwxyz}$  
$\quad \mathtt{A B\Gamma\Delta EZH\Theta}$  
$\quad \mathtt{IK\Lambda MN\Xi O\Pi}$  
$\quad \mathtt{P\Sigma T\Upsilon\Phi X\Psi\Omega}$  
$\quad \mathtt{0123456789}$  
#### 无衬线体  
```cpp
$\mathsf{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\mathsf{abcdefghijklmnopqrstuvwxyz}$  
$\mathsf{A B\Gamma\Delta EZH\Theta}$  
$\mathsf{IK\Lambda MN\Xi O\Pi}$  
$\mathsf{P\Sigma T\Upsilon\Phi X\Psi\Omega}$  
$\mathsf{0123456789}$
 ps:支持大小写英文字母、大写希腊字母和数字。
```
$\quad\mathsf{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\quad\mathsf{abcdefghijklmnopqrstuvwxyz}$  
$\quad\mathsf{A B\Gamma\Delta EZH\Theta}$  
$\quad\mathsf{IK\Lambda MN\Xi O\Pi}$  
$\quad\mathsf{P\Sigma T\Upsilon\Phi X\Psi\Omega}$  
$\quad\mathsf{0123456789}$  
#### 手写体/花体  
```cpp
$\mathcal{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\mathcal{0123456789}$
 ps:支持大写英文字母和数字。
```
$\quad\mathcal{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\quad\mathcal{0123456789}$  
#### $Fraktur$体  
```cpp
$\mathfrak{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\mathfrak{abcdefghijklmnopqrstuvwxyz}$  
$\mathfrak{0123456789}$
 ps:支持大小写英文字母和数字。
```
$\quad\mathfrak{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\quad\mathfrak{abcdefghijklmnopqrstuvwxyz}$  
$\quad\mathfrak{0123456789}$  
#### 小型非斜体字  
```cpp
$\scriptstyle\text{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\scriptstyle\text{abcdefghijklmnopqrstuvwxyz}$  
$\scriptstyle\text{0123456789}$
 ps:支持大小写英文字母和数字，\text见下一栏。
```
$\quad\scriptstyle\text{ABCDEFGHIJKLMNOPQRSTUVWXYZ}$  
$\quad\scriptstyle\text{abcdefghijklmnopqrstuvwxyz}$  
$\quad\scriptstyle\text{0123456789}$  
#### 混合字体
##### 斜体字符  
```cpp
$x y z$
 ps:忽略公式源码中的空格，要强制空格的看下面空格一栏。
```
$\quad x y z$  
##### 非斜体字符  
```cpp
$\text{x y z} \text{中文}$
 ps:不会忽略空格，支持大小写英文字母和数字，以及中文。
```
$\quad\text{x y z}\quad\text{中文}$  
##### 混合斜体与非斜体  
```cpp
$\text{if }n\text{ is even}$
 ps:注意在\text中使用空格来显得更好看，或者可以用强制空格代替。
```
$\quad\text{if }n\text{ is even}$  

------------

### 括号  
#### 普通括号
```cpp
$(\dfrac{1}{2}) (\dfrac{1}{x+\dfrac{2}{3}})$
 ps:对于较大的式子显得比较难看。
```
$\quad(\dfrac{1}{2})\qquad(\dfrac{1}{x+\dfrac{2}{3}})$  
#### 根据式子大小匹配的括号  
```cpp
$\left(\dfrac{1}{2}\right) \left(\dfrac{1}{x+\dfrac{2}{3}}\right)$
```
$\quad\left(\dfrac{1}{2}\right)\qquad\left(\dfrac{1}{x+\dfrac{2}{3}}\right)$  
此功能$($使用\left和\right$)$可以推广到不同的括号：
#### 圆括号/小括号  
```cpp
$\left(\dfrac{1}{2}\right)$
```
$\quad\left(\dfrac{1}{2}\right)$  
#### 方括号/中括号  
```cpp
$\left[\dfrac{1}{2}\right]$
```
$\quad\left[\dfrac{1}{2}\right]$  
#### 花括号/大括号  
```cpp
$\left\{\dfrac{1}{2}\right\}$
 ps:注意大括号要用\{和\}。
```
$\quad\left\{\dfrac{1}{2}\right\}$  
#### 角括号  
```cpp
$\left\langle\dfrac{1}{2}\right\rangle$
 ps:\langle可以用<，\rangle可以用>。
```
$\quad\left\langle\dfrac{1}{2}\right\rangle$  
#### 单竖线/绝对值  
```cpp
$\left|\dfrac{1}{2}\right|$
```
$\quad\left|\dfrac{1}{2}\right|$  
#### 双竖线  
```cpp
$\left\|\dfrac{1}{2}\right\|$
```
$\quad\left\|\dfrac{1}{2}\right\|$  
#### 向下取整  
```cpp
$\left\lfloor\dfrac{1}{2}\right\rfloor$
```
$\quad\left\lfloor\dfrac{1}{2}\right\rfloor$  
#### 向上取整  
```cpp
$\left\lceil\dfrac{1}{2}\right\rceil$
```
$\quad\left\lceil\dfrac{1}{2}\right\rceil$  
#### 斜线  
```cpp
$\left/\dfrac{1}{2}\right/$
```
$\quad\left/\dfrac{1}{2}\right/$  
#### 反斜线  
```cpp
$\left\backslash\dfrac{1}{2}\right\backslash$
```
$\quad\left\backslash\dfrac{1}{2}\right\backslash$  
#### 上下箭头  
```cpp
$\left\uparrow\dfrac{1}{2}\right\uparrow$
```
$\quad\left\uparrow\dfrac{1}{2}\right\uparrow$  
```cpp
$\left\Downarrow\dfrac{1}{2}\right\Downarrow$
```
$\quad\left\Downarrow\dfrac{1}{2}\right\Downarrow$  
```cpp
$\left\updownarrow\dfrac{1}{2}\right\updownarrow$
```
$\quad\left\updownarrow\dfrac{1}{2}\right\updownarrow$  
因为上下箭头太多了，这里就不一一示范了~~（其实是我懒~~。  
#### 混合括号  
其实上述括号都可以混合使用，这里就随便列两个了。  
```cpp
$\left<\dfrac{1}{2}\right/$
```
$\quad\left<\dfrac{1}{2}\right/$  
```cpp
$\left(\dfrac{1}{2},1\right]$
```
$\quad\left(\dfrac{1}{2},1\right]$  
#### 单左括号  
上述括号都适用，这里就随便列一个。  
```cpp
$\left(\dfrac{1}{2}\right.$
```
$\quad\left(\dfrac{1}{2}\right.$  
#### 单右括号  
同上。  
```cpp
$\left.\dfrac{1}{2}\right]$
```
$\quad\left.\dfrac{1}{2}\right]$  
#### 强制括号大小  
```cpp
$\Bigg(\bigg[\Big\{\big<x\big>\Big\}\bigg]\Bigg)$
 ps:即使用\Bigg、\bigg、\Big、\big来控制括号大小。
```
$\quad\Bigg(\bigg[\Big\{\big<x\big>\Big\}\bigg]\Bigg)$  

------------

### 空格  
一般$LaTeX$能自动处理大多数空格，但必要时候需要强制控制大小。  
#### 紧贴
```cpp
$x\!y$
```
$\quad x\!y$  
宽度为$-\frac{m}{6}$  
#### 无空格
```cpp
$xy$
```
$\quad xy$  
宽度为$0$  
#### 小空格
```cpp
$x\,y$
```
$\quad x\,y$  
宽度为$\frac{m}{6}$  
#### 中等空格  
```cpp
$x\;y$
```
$\quad x\;y$  
宽度为$\frac{2m}{7}$  
#### 大空格
```cpp
$x\ y$
```
$\quad x\ y$  
宽度为$\frac{m}{3}$  
#### $quad$空格
```cpp
$x\quad y$
```
$\quad x\quad y$  
宽度为$m$  
#### 两个$quad$空格
```cpp
$x\qquad y$
```
$\quad x\qquad y$  
宽度为$2m$  

------------

### 颜色  
#### 语法  
字体颜色：{\color{色调}表达式}  
背景颜色：{\color{文字色调}\colorbox{背景色调}{表达式(可以打中文)}}
#### 洛谷内支持的颜色(洛谷里有挺多颜色是不支持的，而且有些颜色和$Wiki$上不太一样……)  
${\color{Aquamarine}Aquamarine}$  
${\color{Black}Black}$  
${\color{Blue}Blue}$  
${\color{BlueViolet}BlueViolet}$  
${\color{Brown}Brown}$  
${\color{CadetBlue}CadetBlue}$  
${\color{CornflowerBlue}CornflowerBlue}$  
${\color{Cyan}Cyan}$  
${\color{DarkOrchid}DarkOrchid}$  
${\color{ForestGreen}ForestGreen}$  
${\color{Fuchsia}Fuchsia}$  
${\color{Goldenrod}Goldenrod}$  
${\color{Gold}Gold}$  
${\color{Gray}Gray}$  
${\color{CadetBlue}CadetBlue}$  
${\color{Green}Green}$  
${\color{GreenYellow}GreenYellow}$  
${\color{Lavender}Lavender}$  
${\color{LimeGreen}LimeGreen}$  
${\color{Magenta}Magenta}$  
${\color{Maroon}Maroon}$  
${\color{Orange}Orange}$  
${\color{OrangeRed}OrangeRed}$  
${\color{Orchid}Orchid}$  
${\color{Plum}Plum}$  
${\color{Purple}Purple}$  
${\color{Red}Red}$  
${\color{RoyalBlue}RoyalBlue}$  
${\color{Salmon}Salmon}$  
${\color{SeaGreen}SeaGreen}$  
${\color{SkyBlue}SkyBlue}$  
${\color{SpringGreen}SpringGreen}$  
${\color{Tan}Tan}$  
${\color{Thistle}Thistle}$  
${\color{Turquoise}Turquoise }$  
${\color{Violet}Violet}$  
${\color{White}White}\gets$这是白= =  
${\color{Yellow}Yellow}$  
${\color{YellowGreen}YellowGreen}$  
随便举个例子：  
```cpp
$x=\dfrac{-b\pm\sqrt{\color{Red}b^2-4ac}}{\color{Blue}2a}$
```
$\quad x=\dfrac{-b\pm\sqrt{\color{Red}b^2-4ac}}{\color{Blue}2a}$  
```cpp
$\color{Blue}\colorbox{Yellow}{LaTeX公式大全}$
```
$\quad\color{Blue}\colorbox{Yellow}{LaTeX公式大全}$  

------------

### 把数学公式框起来
```cpp
$$\boxed{\sum\limits_{i = 1}^{n} i = \dfrac{n(n - 1)}{2}}$$

 ps:对于行内模式同样有效，不过大多情况用于独立模式。
```

$$\boxed{\sum\limits_{i = 1}^{n} i = \dfrac{n(n - 1)}{2}}$$

------------

# $End$
