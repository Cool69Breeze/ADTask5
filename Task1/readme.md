forceMultiplier Это множитель силы, который умножается на вектор управления агентом, прежде чем эта сила применяется к телу агента, 
он влияет на то, насколько сильно агент реагирует на действия, предоставленные из внешнего источника

OnEpisodeBegin Этот метод определяет начало нового эпизода

Метод CollectObservations формирует и собирает данные об окружении, которые будут предоставлены агенту как наблюдения

В методе OnActionReceived агент получает награды в зависимости от своих действий и положения в среде. 
Награды служат обратной связью для обучения агента. Обученный агент будет стремиться максимизировать получаемые награды, что в свою очередь влияет на его поведение
