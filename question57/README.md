# Билет №57. Критерий Колмогорова-Смирнова.

Для первой выборки строим эмпирическую функцию

$$ \displaystyle
F^* (x)=
\begin{equation*}
\begin{cases}
0, x < x_1\\
\frac{j}{n}, x_j \leq x \leq x_{j + 1}, j = 1, 2 , \dots, n -1\\
1, x_n \leq x
\end{cases}
\end{equation*}
$$

Аналогично строим для второй — $G^* (y)$. n — количество элементов первой выборки, $m$ — количество элементов второй 

Рассмотрим $\Delta^* (n, m) = \max_{z}[F^* (z) - G^* (z)]; \quad \Delta(n, m) = \sup[F^* (z) - G^* (z)]$

Как доказал Смирнов при $(n, m) \to \infty$

$\displaystyle \Phi_{nm}^* = P\{\sqrt{\frac{nm}{n+m}}\cdot D^* (n, m) < z\} \to 1 - e^{2z^2}$ при $z \geq 0$

$\displaystyle \Phi_{nm} = P\{\sqrt{\frac{nm}{n+m}}\cdot D(n, m) < z\} \to K(z) = \sum_{k = -\infty}^{+\infty}(-1)^ke^{-2k^2z^2}$ при $z \geq 0$

$K(z)$  — функция Колмогорова

## Создатель

Автор расписанного билета: Квист Татьяна

Кто проверил:


## Ресурсы
- лекции Рогова А.А.
