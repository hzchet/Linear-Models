# MyElasticLogisticRegression

Здесь вы можете увидеть мою реализацию ***Логистической Регрессии***, известного алгоритма машинного обучения, используемого в задачах классиификации. Данная реализация содержит в себе **L1** и **L2** регуляризации (**elastic net**), т.е. способы борьбы с переобучением и большими весами модели.

- Имеет схожий интерфейс с классом **LogisticRegression** библиотеки **scikit-learn**
- Использует оптимизацию **Batch Gradient Descent**, давая возможность подбирать размер батча пользователю
- Обучение делится на эпохи, и в течении каждой эпохи алгоритм обучается на каждом из наблюдений ровно один раз. Количество эпох задается пользователем
