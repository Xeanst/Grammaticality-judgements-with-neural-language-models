Репозиторий содержит материалы для статьи [**«Оценка языковой способности нейронных моделей на материале предикативного согласования в русском языке»**] (https://ispranproceedings.elpub.ru/jour/article/view/1559/1418)

**Аннотация:** Исследование нацелено на то, чтобы изучить способность нейронных сетей моделировать грамматику, которая проявляется в функции автоматической оценки грамматичности языковых выражений. В данной работе моделируются правила предикативного согласования по числу в русском языке. Для обучения языковых моделей был создан датасет, включающий искусственно сгенерированные грамматичные и неграмматичные предложения. Мы используем трансферное обучение предобученных нейронных сетей. Результаты показывают, что все рассмотренные модели демонстрируют высокие результаты при дообучении на задачу оценки грамматичности. Точность классификации снижается для предложений с неодушевленными существительными, поскольку для них, в отличие от одушевленных существительных, наблюдается совпадение форм именительного и винительного падежа. Сложность синтаксической структуры оказывается значимой для русскоязычных моделей и модели для славянских языков, но не влияет на распределение ошибок для мультиязычных моделей.

**Содержание репозитория:**
- **data** — скрипт для генерация данных и сами данные;
- **models** — скрипты для обучения и тестирования моделей.

**Для цитирования:** СТУДЕНИКИНА К.А. Оценка языковой способности нейронных моделей на материале предикативного согласования в русском языке. Труды Института системного программирования РАН. 2022;34(6):178-184. https://doi.org/10.15514/ISPRAS-2022-34(6)-14
