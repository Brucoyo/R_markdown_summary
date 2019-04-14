title: "Summary - Markdown Math Symbols"
author: "Bruce Pei"
date: "13/04/2019"

Copyright by Bruce Pei
---
title: "Summary - Markdown Math Symbols"
author: "Bruce Pei"
date: "13/04/2019"
output: html_document
---

|1 ^ and _ Subscript and superscript
|:--- |:---| 
|Example：|`$x^{y^z}=(1+e^x)^{-2xy^w}$`
|Shown as：|$x^{y^z}=(1+e^x)^{-2xy^w}$
|this only change on the right side, if you want to change on both, may consider `\sideset`.
|Example：|`$\sideset{^1_2}{^3_4}\bigotimes$`
|Shown as: |$\sideset{^1_2}{^3_4}\bigotimes$

|2 Brackets / square brackets [ ] / curly brackets {}|
|:--- |:---| 
|In functions `$ $`, ( ) and [ ] are shown the same，but { } needs to be transformed.
|Example：|`$f(x,y) = x^2 + y^2, x\epsilon[0,100]$`
|Shown as：|$f(x,y) = x^2 + y^2, x\epsilon[0,100]$ 
|\left and \right can increase the size of the brackets
|Example1：|`$(\frac{x}{y})^8$，$\left(\frac{x}{y}\right)^8$`
|Demo1：|$(\frac{x}{y})^8$，$\left(\frac{x}{y}\right)^8$


|3 Fraction|
|:--- |:---| 
|`\frac`{Numerator}{Denominator}，or Numerator`\over` Denominator.
|Example：|`$\frac{1}{2x+1}$ or $1\over{2x+1}$`
|Demo：|$\frac{1}{2x+1}$ or $1\over{2x+1}$

|4 Sqrt|
|:--- |:---| 
|Example：|`$\sqrt[9]{3}$ or $\sqrt{3}$`
|Demo：|$\sqrt[9]{3}$ or  $\sqrt{3}$ 

|5 Ellipsis|
|:--- |:---| 
|type 1，`\ldots` as $\ldots$ 
|type 2, `\cdots` $\cdots$ 
|Example：|`$f(x_1, x_2, \ldots, x_n)=x_1^2 + x_2^2+ \cdots + x_n^2$`
|Demo：|$f(x_1, x_2, \ldots, x_n)=x_1^2 + x_2^2+ \cdots + x_n^2$

|6 vector|
|:--- |:---| 
|Example：|`$\vec{a} \cdot \vec{b}=0$`
|Demo:| $\vec{a} \cdot \vec{b}=0$

|7 Integral|
|:--- |:---| 
|Example：|`$\int_0^1x^2{\rm d}x $`
|Demo：|$\int_0^1x^2{\rm d}x $ 

|8 Limit
|:--- |:---| 
|Example：|`$\lim_{n\rightarrow+\infty}\frac{1}{n(n+1)}$`
|Demo：| $\lim_{n\rightarrow+\infty}\frac{1}{n(n+1)}$

|9 Sum
|:--- |:---| 
|Example：|`$\sum_1^n\frac{1}{x^2}，\prod_{i=0}^n\frac{1}{x^2}$`
|Demo：|$\sum_1^n\frac{1}{x^2}，\prod_{i=0}^n\frac{1}{x^2}$

|10 Greek alphabet
|:--- |:---| 
|Example：|`$$\alpha　A　\beta　B　\gamma　\Gamma　\delta　\Delta　\epsilon　E$$`
|Demo：|$$\alpha　A　\beta　B　\gamma　\Gamma　\delta　\Delta　\epsilon　E$$
|Example：|`$$\varepsilon　　\zeta　Z　\eta　H　\theta　\Theta　\vartheta \iota　I$$`
|Demo:|$$\varepsilon　　\zeta　Z　\eta　H　\theta　\Theta　\vartheta \iota　I$$ 
|Example：| `$$\kappa　K　\lambda　\Lambda　\mu　M　\nu　N \xi　\Xi`
|Demo: | $$\kappa　K　\lambda　\Lambda　\mu　M　\nu　N \xi　\Xi$$
|Example：|`o　O　\pi　\Pi　\varpi　　\rho　P \varrho　　\sigma　\Sigma　\varsigma`
|Demo:| $$o　O　\pi　\Pi　\varpi　　\rho　P \varrho　　\sigma　\Sigma　\varsigma$$
|Example：|`\tau　T　\upsilon　\Upsilon \phi　\Phi　\varphi　　\chi　X　\psi　\Psi　\omega　\Omega$$`
|Demo: | $$\tau　T　\upsilon　\Upsilon \phi　\Phi　\varphi　　\chi　X　\psi　\Psi　\omega　\Omega$$

### 11 Summary of math symbols

| General symbols | Markdown | 
|:--- |:---:| 
|$\pm$|`$\pm$` 
|$\times$|`$\times$` 
|$\div$|`$\div$`
|$\mid$|`$\mid$`
|$\cdot$|`$\cdot$` 
|$\circ$|`$\circ$` 
|$\ast$|`$\ast$` 
|$\bigodot$|`$\bigodot$` 
|$\bigotimes$|`$\bigotimes$` 
|$\bigoplus$|`$\bigoplus$` 
|$\leq$|`$\leq$` 
|$\geq$|`$\geq$` 
|$\neq$|`$\neq$` 
|$\approx$|`$\approx$` 
|$\equiv$|`$\equiv$` 
|$\sum$|`$\sum$` 
|$\prod$|`$\prod$` 
|$\coprod$|`$\coprod$`

| Set | Markdown | 
|:--- |:---:| 
|$\emptyset$|`$\emptyset$` 
|$\in$|`$\in$`
|$\notin$|`$\notin$` 
|$\subset$|`$\subset$` 
|$\supset$|`$\supset$` 
|$\subseteq$|`$\subseteq$` 
|$\supseteq$|`$\supseteq$` 
|$\bigcap$|`$\bigcap$` 
|$\bigcup$ |`$\bigcup$` 
|$\bigvee$ |`$\bigvee$` 
|$\bigwedge$ |`$\bigwedge$` 
|$\biguplus$ |`$\biguplus$` 
|$\bigsqcup$|`$\bigsqcup$`

| Logarithm | Markdown | 
|:--- |:---:| 
|$\log$ | `$\log$` 
|$\lg$| `$\lg$` 
|$\ln$| `$\ln$`

| Trigonometric functions   | Markdown | 
| --- |:---| 
|$\bot$|`$\bot$` 
|$\angle$|`$\angle$` 
|$30^\circ$|`$30^\circ$` 
|$\sin$|`$\sin$` 
|$\cos$|`$\cos$` 
|$\tan$|`$\tan$` 
|$\cot$|`$\cot$` 
|$\sec$|`$\sec$` 
|$\csc$|`$\csc$`

| Calculus   | Markdown | 
| --- |:---:| 
|$y\prime x$|`$\prime$` 
|$\int$|`$\int$` 
|$\iint$ |`$\iint$` 
|$\iiint$|`$\iiint $`
|$\iiiint$|$\iiiint $`
|$\oint$ |`$\oint$` 
|$\lim$ |`$\lim$`
|$\infty$ |`$\infty$` 
|$\nabla$|`$\nabla$`

| Logical connective   | Markdown | 
| --- |:---:| 
|$\because$|`$\because $`
|$\therefore$ |`$\therefore$` 
|$\forall$ |`$\forall $`
|$\exists$ |`$\exists $`
|$\not=$|`$\not= $`
|$\not>$|`$\not> $`
|$\not\subset$|`$\not\subset$`

 
| Hat：   | Markdown | 
| --- |:---:| 
| $\hat{y}$| `$\hat{y}$`
| $\check{y}$| `$\check{y}$`
| $\breve{y}$| `$\breve{y}$`
| $\bar{y}$| `$\bar{y}$`

| Overlines / Underlines： | Markdown
| --- |:---:| 
|$\overline{a+b+c+d}$  |`$\overline{a+b+c+d}$`
|$\underline{a+b+c+d}$ |`$\underline{a+b+c+d}$`
|$\overbrace{a+\underbrace{b+c}_{1.0}+d}^{2.0}$ |`$\overbrace{a+\underbrace{b+c}_{1.0}+d}^{2.0}$`

| Arrow：   | Markdown | 
| --- |:---:| 
| ↑      | `$\uparrow$`
| ↓      | `$\downarrow$` 
| ⇑    | `$\Uparrow $`
| ⇓    | `$\Downarrow $`
| →    | `$\rightarrow $`
| ←     | `$\leftarrow $`
| ⇒ | `$\Rightarrow $`
| ⇐ | `$\Leftarrow $`
| ⟶ | `$\longrightarrow $`
| ⟵ | `$\longleftarrow $`
| ⟹| `$\Longrightarrow $`
| ⟸ | `$\Longleftarrow$`


### 12 Background color

<table><tr><td bgcolor=orange> background color is orange</td></tr></table> `<table><tr><td bgcolor=orange> background color is orange</td></tr></table>`

<table><tr><td bgcolor= Lightblue > background color is Lightblue </td></tr></table> `<table><tr><td bgcolor= Lightblue > background color is Lightblue </td></tr></table>`


### 13 Font

| Font        | Original           | NEW  |
| :--- |:---| :---|
| Papyrus     | LOVE | <span style="font-family:Papyrus; font-size:1em;">LOVE!</span> `<span style="font-family:Papyrus; font-size:1em;">LOVE!</span>`
| Bebas Neue | LOVE      |    <span style="font-family: 'Bebas Neue'; font-size: 1em;">LOVE!</span> `<span style="font-family: 'Bebas Neue'; font-size: 1em;">LOVE!</span>`| 
| Black | LOVE | $\bf LOVE$ `$\bf LOVE$`|
| Italic | LOVE | $\it LOVE$ `$\it LOVE$`|
| Beauty | LOVE | $\cal LOVE$ `$\cal LOVE$`|
| Print | LOVE | $\tt LOVE$ `$\tt LOVE$`|

The end!


