## Описание

Этот проект демонстрирует создание системы для управления потоками, содержащими списки учебных групп, с использованием принципов ООП в Java. В проекте реализованы классы для потоков, учебных групп, а также сервисы и контроллеры для управления и сортировки потоков.

## Структура проекта

Проект состоит из следующих классов:

### Классы

1. **StudyGroup**:
    - Представляет учебную группу.

2. **Stream**:
    - Представляет поток, содержащий список учебных групп.

3. **StreamComparator**:
    - Реализует интерфейс `Comparator` для сравнения количества групп в потоках.

4. **StreamService**:
    - Содержит метод для сортировки списка потоков с использованием `StreamComparator`.

5. **Controller**:
    - Управляет потоками и использует `StreamService` для их сортировки.
