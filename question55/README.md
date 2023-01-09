# Билет №55. Критерий Колмогорова

Пусть $x_1, x_2, \dots, x_n$ — выборка, $F_0(x)$ — непрерывная функция 
$\Delta n = \sup_{-\infty <x < +\infty}|F_n(x) - F_0(x)|$ — расстояние между теоретической и эмпирическими функциями распределения. 
$\Delta n$ — статистика Колмогорова.

По теореме колмогорова $\lim P = (\sqrt{n}\cdot \Delta n < z) = K(z)$, где $K(z) = \sum_{k = -\infty}^{+\infty}-(-1)^k e^{-2k^2z}$ — распределение Колмогорова, значения протабулированы.

**Алгоритм проверки гипотезы**

1. $\Delta n = \max_{1 < k < n}\left[\frac{k}{n}- F_0(x_k), |F_0(x_k) - \frac{k -1}{n}| \right]$
2. Рассмотрим $\alpha: K(z) = 1 - \alpha.$ Если $\sqrt n\cdot \Delta n < z$, гипотеза не противоречит, если $\sqrt n\cdot \Delta n \geq z$, то противоречит.
$x_{k-1} < x< x_k; F_n(x) = \frac{k-1}{n}$

### Критерии однородности и независимости

Пусть $x_1, x_2, \dots, x_n, F_1(x); y_1, y_2, \dots, y_n, F_2(y)$. Проверить  $H_0 = \{F_1(x) = F_2(y)\}$

## Создатель

Автор расписанного билета: Квист Татьяна

Кто проверил:


## Ресурсы
- лекции Рогова А.А.