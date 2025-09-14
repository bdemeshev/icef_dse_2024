$$
\Loss(y, \hat y) = \frac{1}{2}\sum (y_i - \hat y_i)^2
$$

$$
-\grad \Loss = (y_1 - \hat y_1, y_2 - \hat y_2,  \ldots, y_n - \hat y_n)
$$
Вектор остатков — это минус градиент квадратичной функции потерь, если её поделить пополам.

* Рассказать про градиентный бустинг на метрике?
* изложить сначала на деревьях из одного узла, потом xgboost?
* изложить явно на примере с двумя классами 



Источники:
https://www.chengli.io/tutorials/gradient_boosting.pdf
есть ручные вычисления с многими классами

https://www.cmi.ac.in/~madhavan/courses/dmml2021apr/literature/Vihar-Kurama-blog-Gradient-Boosting-Classification.pdf
разобранный пример с бинарной классицикацией
ужасный ворд

https://www.frontiersin.org/journals/neurorobotics/articles/10.3389/fnbot.2013.00021/full
аккуратные точные алгоритмы

https://www.cse.chalmers.se/~richajo/dit866/files/gb_explainer.pdf
три странички с короткими алгоритмами

