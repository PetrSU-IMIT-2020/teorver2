# Билет №47. Доверительный интервал для мат. ожидания при известной дисперсии нормально распределенной генеральной совокупности.

**Теорема 1 Фишера**

Пусть $X_1$, $X_2$, ..., $X_n$ - независимые случайные величины $\sim N(a,\sigma)$

Рассмотрим $\overline{x} = \frac{1}{n}\sum\limits_{i=1}^n X_i$ (выборочное среднее) и $m_2 = \frac{1}{n}\sum\limits_{i=1}^n (X_i - \overline{x})^2$ (выборочная дисперсия)

$\overline{x}$ и $m_2$ - независимые случайные величины

$\Huge\overline{x} \sim N(a,\frac{\sigma}{\sqrt{n}})$ - выборочное среднее распределено по нормальному закону с параметрами a , $\frac{\sigma}{\sqrt{n}}$

$\Huge\frac{nm_2}{\sigma^2} \sim \chi_{n-1}^2$ - выборочная дисперсия имеет распределение хи-квадрат с $n-1$ степенями свободы

![](../question46/graph0.png)

Пусть случайная велчина $\xi \sim N(\alpha,\sigma), \alpha = ?$

По теореме 1 Фишера $$\overline{x} \sim N (\alpha, \frac{\sigma}{\sqrt{n}})$$

Рассмотрим $\frac{\overline{x} - \alpha}{\sigma / \sqrt{n}} \sim N(0,1)$

Задаем квантиль распространения Лапласа $\rho$

$$\displaystyle P(|{\frac{\overline{x} - \alpha}{\sigma / \sqrt{n}}}| < t_\rho) = \rho => P(-t_\rho < \frac{\overline{x} - \alpha}{\sigma / \sqrt{n}} < t_\rho) = P(\overline{x} - t_\rho \frac{\sigma}{\sqrt{n}} < \alpha < \overline{x} + t_\rho \frac{\sigma}{\sqrt{n}})$$

$\displaystyle (\overline{x} - t_\rho \frac{\sigma}{\sqrt{n}}, \overline{x} + t_\rho \frac{\sigma}{\sqrt{n}})$ - доверительный интервал

$t_\rho \frac{\sigma}{\sqrt{n}}$ - точность оценки

## Создатель

Автор расписанного билета: Лисицкий Олег

Кто проверил:


## Ресурсы
- лекции Рогова А.А.
