**Проект:** Обучение с учителем - качество модели

**Цель:** Разработать и внедрить систему персонализированных предложений для постоянных клиентов интернет-магазина «В один клик», чтобы повысить их покупательскую активность и удержать существующих клиентов.

**Задачи:**
1. Разработать модель, которая предскажет вероятность снижения покупательской активности.
2. Выделить сегмент покупателей, проанализировать его и предложить, как увеличить его покупательскую активность.

**ИТОГ**

1. **Обработка данных**:
    
    - Были устранены неявные дубликаты   
    - Исправлены орфографические ошибки

    
2. **Поиск лучшей модели**:
    
    - Была проведена подготовка тренировочной и валидационной выборки. 
    - Создан единый пайплан, который содержит в себе масштабирование входных признаков и 4 модели.
    - Использованы два метода подбора гиперпараметров:
        - _RandomSearchCV_     
        - _GridSearchCV_     
    - Лучшая модель -- **SVC** с метрикой __roc_auc = 0.912__
    
    
3. **Рекомендации**:

    - Разработка специальных акций и предложений, ориентированных на популярные категории товаров, что может стимулировать пользователей к совершению покупок.
    - Предложение аналогичных товаров по более низкой цене, так как данные пользователи стараются взять товары подешевле.    
    - Оптимизация процесса оформления заказа для снижения количества неоплаченных товаров в корзине, возможно, с помощью напоминаний или предложений по завершению покупки.
    - Улучшение контента на сайте, чтобы увеличить время, проводимое пользователями на платформе, и повысить их вовлеченность
