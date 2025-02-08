# ✨ LaTeX 数学公式语法大全 2.0 📘

[在线阅读](https://ahaknow.com/posts/know/latex/)

[两年前的版本](OldVersion.md)，说来惭愧，当时Push完就没再管了，这次重新整理了一下，助人也助己，希望对大家有所帮助~

---

# 📘 **LaTeX 语法**
## **📐 1. LaTeX 数学模式**

### **1.1. 行内数学模式**

在文本中插入数学公式：

```latex
$E=mc^2$
```

$E=mc^2$ 行内模式的数学公式，适用于正文中的数学表达。

### **1.2. 独立数学模式**

使数学公式独占一行：

```latex
$$
E=mc^2
$$
```

独立模式的数学公式，适用于单独一行的数学表达。

$$
E=mc^2
$$

### **1.3. 带编号公式**

```latex
\begin{equation}
E=mc^2
\end{equation}
```

$$
\begin{equation}
E=mc^2
\end{equation}
$$

带有编号的数学公式，适用于论文或报告中公式引用。（Markdown中可能无法显示编号 ）

---

## **🔣 2. 保留字符**

LaTeX 环境中具有特殊含义的保留字符，不能直接使用，必须通过指定的语法实现：

| 符号  | LaTeX 代码     | 中文说明           |
| --- | ------------ | -------------- |
| #   | `\#`         | 井号，数学环境中无特殊含义  |
| $   | `\$`         | 美元符号，通常用于货币符号  |
| %   | `\%`         | 百分号，表示百分比      |
| &   | `\&`         | 与符号，通常用于逻辑表达   |
| _   | `\_`         | 下划线，LaTeX 需要转义 |
| {}  | `\{ \}`      | 花括号，用于分组       |
| \   | `\backslash` | 反斜杠，LaTeX 转义符  |

---

## **🔠 3. 希腊字母**

### **3.1. 小写希腊字母**

| 符号            | LaTeX 代码      | 中文音译              |
| ------------- | ------------- | ----------------- |
| $\alpha$      | `\alpha`      | 阿尔法               |
| $\beta$       | `\beta`       | 贝塔                |
| $\gamma$      | `\gamma`      | 伽马                |
| $\delta$      | `\delta`      | 德尔塔               |
| $\epsilon$    | `\epsilon`    | 艾普西龙（普通 epsilon）  |
| $\varepsilon$ | `\varepsilon` | 伪艾普西龙（变体 epsilon） |
| $\zeta$       | `\zeta`       | 截塔                |
| $\eta$        | `\eta`        | 伊塔                |
| $\theta$      | `\theta`      | 西塔                |
| $\vartheta$   | `\vartheta`   | 变体西塔              |
| $\iota$       | `\iota`       | 约塔                |
| $\kappa$      | `\kappa`      | 卡帕                |
| $\lambda$     | `\lambda`     | 兰布达               |
| $\mu$         | `\mu`         | 缪                 |
| $\nu$         | `\nu`         | 纽                 |
| $\xi$         | `\xi`         | 克西                |
| $\pi$         | `\pi`         | 派（圆周率）            |
| $\varpi$      | `\varpi`      | 变体派               |
| $\rho$        | `\rho`        | 罗                 |
| $\varrho$     | `\varrho`     | 变体罗               |
| $\sigma$      | `\sigma`      | 西格玛               |
| $\varsigma$   | `\varsigma`   | 终结西格玛（变体 sigma）   |
| $\tau$        | `\tau`        | 陶                 |
| $\upsilon$    | `\upsilon`    | 宇普西龙              |
| $\phi$        | `\phi`        | 菲                 |
| $\varphi$     | `\varphi`     | 变体菲               |
| $\chi$        | `\chi`        | 氚（发音接近“开”）        |
| $\psi$        | `\psi`        | 普赛                |
| $\omega$      | `\omega`      | 欧米伽               |

### **3.2. 大写希腊字母**

|符号|LaTeX 代码|中文音译|
|---|---|---|
|$\Gamma$|`\Gamma`|伽马（大写）|
|$\Delta$|`\Delta`|德尔塔（大写）|
|$\Theta$|`\Theta`|西塔（大写）|
|$\Lambda$|`\Lambda`|兰布达（大写）|
|$\Xi$|`\Xi`|克西（大写）|
|$\Pi$|`\Pi`|派（大写，数学常用于求和）|
|$\Sigma$|`\Sigma`|西格玛（大写，数学常用于求和）|
|$\Upsilon$|`\Upsilon`|宇普西龙（大写）|
|$\Phi$|`\Phi`|菲（大写）|
|$\Psi$|`\Psi`|普赛（大写）|
|$\Omega$|`\Omega`|欧米伽（大写，数学物理常用）|

---

## **➗ 4. 二元运算符**

| 符号           | LaTeX 代码     | 中文说明          |
| ------------ | ------------ | ------------- |
| $+$          | `+`          | 加号            |
| $-$          | `-`          | 减号            |
| $\times$     | `\times`     | 乘号            |
| $\div$       | `\div`       | 除号            |
| $\cdot$      | `\cdot`      | 乘积点           |
| $\oplus$     | `\oplus`     | 直和（用于向量空间、群论） |
| $\ominus$    | `\ominus`    | 直差            |
| $\otimes$    | `\otimes`    | 直积            |
| $\oslash$    | `\oslash`    | 直除            |
| $\odot$      | `\odot`      | 圆点乘法          |
| $\star$      | `\star`      | 星乘法           |
| $\circ$      | `\circ`      | 复合映射          |
| $\bullet$    | `\bullet`    | 实心点（乘法或列表符号）  |
| $\pm$        | `\pm`        | 正负号           |
| $\mp$        | `\mp`        | 负正号           |
| $\bigoplus$  | `\bigoplus`  | 直和运算符（大运算符版本） |
| $\bigotimes$ | `\bigotimes` | 直积运算符（大运算符版本） |
| $\bigodot$   | `\bigodot`   | 直乘运算符（大运算符版本） |

---

## **⚖️ 5. 二元关系符**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$=$|`=`|等于|
|$\neq$|`\neq`|不等于|
|$\approx$|`\approx`|约等于|
|$\equiv$|`\equiv`|恒等于|
|$<$|`<`|小于|
|$>$|`>`|大于|
|$\leq$|`\leq`|小于等于|
|$\geq$|`\geq`|大于等于|
|$\ll$|`\ll`|远小于|
|$\gg$|`\gg`|远大于|
|$\prec$|`\prec`|先于（偏序关系）|
|$\succ$|`\succ`|后于（偏序关系）|
|$\preceq$|`\preceq`|小于等于（偏序）|
|$\succeq$|`\succeq`|大于等于（偏序）|
|$\sim$|`\sim`|相似于|
|$\nsim$|`\nsim`|不相似|
|$\simeq$|`\simeq`|同构|
|$\asymp$|`\asymp`|渐近等于|
|$\propto$|`\propto`|成比例|

---

## **🧠 6. 逻辑符号**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$\wedge$|`\wedge`|逻辑与（合取）|
|$\vee$|`\vee`|逻辑或（析取）|
|$\neg$|`\neg`|逻辑非（否定）|
|$\Rightarrow$|`\Rightarrow`|蕴含（如果...那么）|
|$\Leftrightarrow$|`\Leftrightarrow`|当且仅当|
|$\forall$|`\forall`|对所有|
|$\exists$|`\exists`|存在|
|$\nexists$|`\nexists`|不存在|
|$\top$|`\top`|逻辑真|
|$\bot$|`\bot`|逻辑假|

---

## **📦 7. 集合符号**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$\emptyset$|`\emptyset`|空集|
|$\in$|`\in`|属于|
|$\notin$|`\notin`|不属于|
|$\subseteq$|`\subseteq`|子集|
|$\subset$|`\subset`|真子集|
|$\nsubseteq$|`\nsubseteq`|不是子集|
|$\supset$|`\supset`|包含|
|$\supseteq$|`\supseteq`|超集|
|$\nsupseteq$|`\nsupseteq`|不是超集|
|$\cup$|`\cup`|并集|
|$\cap$|`\cap`|交集|
|$\setminus$|`\setminus`|差集|
|$\bigcup$|`\bigcup`|大并集|
|$\bigcap$|`\bigcap`|大交集|

---

## **↔️ 8. 箭头符号**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$\to$|`\to`|右箭头|
|$\leftarrow$|`\leftarrow`|左箭头|
|$\Rightarrow$|`\Rightarrow`|右蕴含箭头|
|$\Leftarrow$|`\Leftarrow`|左蕴含箭头|
|$\leftrightarrow$|`\leftrightarrow`|左右箭头|
|$\Leftrightarrow$|`\Leftrightarrow`|双向蕴含箭头|
|$\longrightarrow$|`\longrightarrow`|长右箭头|
|$\longleftarrow$|`\longleftarrow`|长左箭头|
|$\mapsto$|`\mapsto`|映射箭头|
|$\longmapsto$|`\longmapsto`|长映射箭头|
|$\uparrow$|`\uparrow`|向上箭头|
|$\downarrow$|`\downarrow`|向下箭头|
|$\updownarrow$|`\updownarrow`|上下箭头|
|$\Uparrow$|`\Uparrow`|向上双箭头|
|$\Downarrow$|`\Downarrow`|向下双箭头|
|$\Updownarrow$|`\Updownarrow`|上下双箭头|

## **🔢 9. 分数**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$\frac{a}{b}$|`\frac{a}{b}`|普通分数|
|$\dfrac{a}{b}$|`\dfrac{a}{b}`|强制分数（适用于行内公式）|
|$\tfrac{a}{b}$|`\tfrac{a}{b}`|小型分数（适用于较小的公式）|

---

## **✔️ 10. 根式**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$\sqrt{x}$|`\sqrt{x}`|平方根|
|$\sqrt[n]{x}$|`\sqrt[n]{x}`|n 次方根|

---

## **📈 11. 指数与对数**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$a^b$|`a^b`|指数|
|$e^x$|`e^x`|自然指数|
|$\log x$|`\log x`|对数（默认底数为10）|
|$\ln x$|`\ln x`|自然对数（底数为 e）|
|$\log_a b$|`\log_a b`|底数 a 的对数|

---

## **📉 12. 微分与导数**

| 符号                              | LaTeX 代码                        | 中文说明       |
| ------------------------------- | ------------------------------- | ---------- |
| $\frac{d}{dx} f(x)$             | `\frac{d}{dx} f(x)`             | 一阶导数       |
| $\frac{d^2}{dx^2} f(x)$         | `\frac{d^2}{dx^2} f(x)`         | 二阶导数       |
| $\frac{\partial f}{\partial x}$ | `\frac{\partial f}{\partial x}` | 偏导数        |
| $\nabla f$                      | `\nabla f`                      | 梯度         |
| $\Delta f$                      | `\Delta f`                      | 拉普拉斯算子     |
| $\dot{x}$                       | `\dot{x}`                       | 一阶导数（牛顿记号） |
| $\ddot{x}$                      | `\ddot{x}`                      | 二阶导数（牛顿记号） |

---

## **🔝 13. 极限**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$\lim_{x \to a} f(x)$|`\lim_{x \to a} f(x)`|极限|
|$\lim_{x \to \infty} f(x)$|`\lim_{x \to \infty} f(x)`|无穷极限|

---

## **∫ 14. 积分**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$\int f(x)dx$|`\int f(x)dx`|不定积分|
|$\int_{a}^{b} f(x)dx$|`\int_{a}^{b} f(x)dx`|定积分|
|$\iint f(x,y)dxdy$|`\iint f(x,y)dxdy`|二重积分|
|$\iiint f(x,y,z)dxdydz$|`\iiint f(x,y,z)dxdydz`|三重积分|

---

## **✍️ 15. 矩阵**

| 符号                                            | LaTeX 代码                                       | 中文说明  |
| --------------------------------------------- | ---------------------------------------------- | ----- |
| $\begin{bmatrix} a & b \ c & d \end{bmatrix}$ | `\begin{bmatrix} a & b \\ c & d \end{bmatrix}` | 方括号矩阵 |
| $\begin{pmatrix} a & b \ c & d \end{pmatrix}$ | `\begin{pmatrix} a & b \\ c & d \end{pmatrix}` | 圆括号矩阵 |
| $\begin{vmatrix} a & b \ c & d \end{vmatrix}$ | `\begin{vmatrix} a & b \\ c & d \end{vmatrix}` | 行列式   |
| $\begin{Vmatrix} a & b \ c & d \end{Vmatrix}$ | `\begin{Vmatrix} a & b \\ c & d \end{Vmatrix}` | 双竖线矩阵 |
| $\begin{matrix} a & b \ c & d \end{matrix}$   | `\begin{matrix} a & b \\ c & d \end{matrix}`   | 无括号矩阵 |

---

## ➡️ 16. **向量**

### **16.1 向量的加粗表示**

| 符号                    | LaTeX 代码              | 中文说明                                |
| --------------------- | --------------------- | ----------------------------------- |
| $\mathbf{v}$          | `\mathbf{v}`          | 向量，适用于字母                            |
| $\mathbf{v}$          | `\bm{v}`              | 加粗向量（适用于所有数学符号，需 `\usepackage{bm}`） |
| $\boldsymbol{\alpha}$ | `\boldsymbol{\alpha}` | 加粗希腊字母（适用于 `\alpha, \beta` 等）       |

### **16.2. 向量的箭头表示**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$\vec{v}$|`\vec{v}`|向量符号，表示带箭头的向量|
|$\overrightarrow{AB}$|`\overrightarrow{AB}`|表示从 A 指向 B 的向量|
|$\overleftarrow{AB}$|`\overleftarrow{AB}`|表示从 B 指向 A 的向量|

### **16.3 单位向量**

单位向量表示方向向量，通常用 **加帽符号**：

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$\hat{v}$|`\hat{v}`|单位向量|
|$\hat{i}, \hat{j}, \hat{k}$|`\hat{i}, \hat{j}, \hat{k}`|直角坐标系中的标准基向量|

### **16.4 向量的点积与叉积**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$\mathbf{a} \cdot \mathbf{b}$|`\mathbf{a} \cdot \mathbf{b}`|向量的点积|
|$\mathbf{a} \times \mathbf{b}$|`\mathbf{a} \times \mathbf{b}`|向量的叉积|

---

## 🔄 **17. 方程与方程组**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$\begin{align} x + y &= 2 \ x - y &= 0 \end{align}$|`\begin{align} x + y &= 2 \\ x - y &= 0 \end{align}`|对齐的方程组|
|$\begin{cases} ax + by = c \ dx + ey = f \end{cases}$|`\begin{cases} ax + by = c \\ dx + ey = f \end{cases}`|分段定义或方程组|

---

## ✏️ **18. 空格与换行**

| 符号                       | LaTeX 代码                 | 中文说明      |
| ------------------------ | ------------------------ | --------- |
| $a\ b$                   | `a\ b`                   | 小空格       |
| $a\quad b$               | `a\quad b`               | 大空格       |
| $a\qquad b$              | `a\qquad b`              | 超大空格      |
| $a\ b$                   | `a\\ b`                  | 换行        |
| $a,b$                    | `a\,b`                   | 细小空格      |
| $a!b$                    | `a\!b`                   | 负空格（缩小间距） |
| $\text{This is a~test.}$ | `\text{This is a~test.}` | 硬空格       |

---

## 🎨 **19. 颜色**

|符号|LaTeX 代码|中文说明|
|---|---|---|
|$\textcolor{red}{text}$|`\textcolor{red}{text}`|颜色（红色）|
|$\textcolor{blue}{text}$|`\textcolor{blue}{text}`|颜色（蓝色）|
|$\color{green}text$|`\color{green}text`|颜色（绿色）|

---

## 🖍️ **20. 字体**

| 符号            | LaTeX 代码      | 中文说明       |
| ------------- | ------------- | ---------- |
| $\mathbf{x}$  | `\mathbf{x}`  | 加粗         |
| $\mathit{x}$  | `\mathit{x}`  | 斜体         |
| $\mathcal{L}$ | `\mathcal{L}` | 手写体        |
| $\mathbb{R}$  | `\mathbb{R}`  | 黑板体（常用于数集） |
| $\mathrm{x}$  | `\mathrm{x}`  | 直立体        |
| $\mathtt{x}$  | `\mathtt{x}`  | 打字机字体      |
| $\mathscr{L}$ | `\mathscr{L}` | 花体（数学符号）   |

---




# 💎**完整示例**

## **🌊 1. 线性代数**

### **1.1 矩阵乘法**

给定两个矩阵 $A \in \mathbb{R}^{m \times n}$ 和 $B \in \mathbb{R}^{n \times p}$，它们的**矩阵乘法**定义如下：

```latex
$$
C = AB, \quad C_{ij} = \sum_{k=1}^{n} A_{ik} B_{kj}, \quad C \in \mathbb{R}^{m \times p}
$$
```

$$
C = AB, \quad C_{ij} = \sum_{k=1}^{n} A_{ik} B_{kj}, \quad C \in \mathbb{R}^{m \times p}
$$

**说明**：矩阵 $C$ 的元素 $C_{ij}$ 由矩阵 $A$ 的第 $i$ 行与矩阵 $B$ 的第 $j$ 列按**对应元素相乘后求和**得到。

---

### **1.2 特征值与特征向量**

对于方阵 $A \in \mathbb{R}^{n \times n}$，如果存在非零向量 $\bm{v}$ 和标量 $\lambda$ 使得：

```latex
$$
A\mathbf{v} = \lambda \mathbf{v}
$$

```

则称 $\lambda$ 为矩阵 $A$ 的**特征值**，$\mathbf{v}$ 为对应的**特征向量**。

$$
A\mathbf{v} = \lambda \mathbf{v}
$$

**说明**：当矩阵 $A$ 作用于向量 $\mathbf{v}$ 上时，$\mathbf{v}$ 仅仅被缩放（即乘以特征值 $\lambda$），方向不变。

---

### **1.3 奇异值分解（SVD）**

任意矩阵 $A \in \mathbb{R}^{m \times n}$ 可分解为：

```latex
$$
A = U \Sigma V^T
$$
```

其中：

- $U \in \mathbb{R}^{m \times m}$ 是正交矩阵，
- $V \in \mathbb{R}^{n \times n}$ 是正交矩阵，
- $\Sigma$ 是对角矩阵，包含奇异值 $\sigma_i$。

$$
A = U \Sigma V^T
$$

**说明**：奇异值分解（SVD）是一种强大的矩阵分解方法，广泛用于**降维、压缩、信号处理等**。

---

## **🎲 2. 概率统计**

### **2.1 贝叶斯定理**

对于事件 $A$ 和 $B$，如果 $P(B) > 0$，则贝叶斯定理表示为：

```latex
$$
P(A \mid B) = \frac{P(B \mid A) P(A)}{P(B)}
$$
```

$$
P(A \mid B) = \frac{P(B \mid A) P(A)}{P(B)}
$$

**说明**：贝叶斯定理是概率论中最重要的公式之一，广泛用于**机器学习、医学诊断、自然语言处理等**领域。

---

### **2.2 期望与方差**

#### **2.2.1 期望**

设随机变量 $X$ 服从概率分布 $P(X)$，则：

```latex
$$
\mathbb{E}[X] = \sum_{x} x P(X = x)
$$
```

$$
\mathbb{E}[X] = \sum_{x} x P(X = x)
$$

**说明**：数学期望表示随机变量 $X$ 的**加权平均值**，即它的**平均趋势**。

#### **2.2.2 方差**

随机变量 $X$ 的方差定义为：

```latex
$$
\mathrm{Var}(X) = \mathbb{E}[(X - \mathbb{E}[X])^2]
$$
```

$$
\mathrm{Var}(X) = \mathbb{E}[(X - \mathbb{E}[X])^2]
$$

**说明**：方差度量了随机变量 $X$ **偏离均值的程度**，方差越大，数据的离散性越强。

---

### **2.3 高斯分布（正态分布）**

随机变量 $X$ 服从均值 $\mu$，方差 $\sigma^2$ 的高斯分布（正态分布），其概率密度函数（PDF）为：

```latex
$$
p(x) = \frac{1}{\sqrt{2 \pi \sigma^2}} \exp \left(-\frac{(x - \mu)^2}{2\sigma^2} \right)
$$
```

$$
p(x) = \frac{1}{\sqrt{2 \pi \sigma^2}} \exp \left(-\frac{(x - \mu)^2}{2\sigma^2} \right)
$$

**说明**：高斯分布是**最重要的概率分布**之一，在**自然科学、工程、机器学习等领域**中应用广泛。

---

## **🤖 3. 机器学习**

### **3.1 线性回归模型**

在**线性回归模型**中，如果试图找到一个线性函数来拟合数据点 $(x_i, y_i)$，那么数学表达式如下：

```latex
$$
y = w^T x + b
$$
```

$$
y = w^T x + b
$$

使用最小二乘法（OLS）来估计参数 $w$，会用到最小化**均方误差（MSE）**：

```latex
$$
L(w, b) = \frac{1}{N} \sum_{i=1}^{N} (y_i - (w^T x_i + b))^2
$$
```

$$
L(w, b) = \frac{1}{N} \sum_{i=1}^{N} (y_i - (w^T x_i + b))^2
$$

**说明**：线性回归是**机器学习最基础的回归模型**，在**统计建模、预测分析**等领域广泛应用。

---

### **3.2 Kullback-Leibler (KL) 散度**

KL 散度用于衡量两个概率分布 $P(x)$ 和 $Q(x)$ 之间的差异，定义如下：

```latex
$$
D_{KL}(P \parallel Q) = \sum_x P(x) \log \frac{P(x)}{Q(x)}
$$
```

$$
D_{KL}(P \parallel Q) = \sum_x P(x) \log \frac{P(x)}{Q(x)}
$$

或者对于连续概率分布：

```latex
$$
D_{KL}(P \parallel Q) = \int P(x) \log \frac{P(x)}{Q(x)} dx
$$
```

$$
D_{KL}(P \parallel Q) = \int P(x) \log \frac{P(x)}{Q(x)} dx
$$

**说明**：KL 散度用于衡量两个概率分布之间的**相对熵**，在**信息论、概率统计、机器学习**等领域中应用广泛。
