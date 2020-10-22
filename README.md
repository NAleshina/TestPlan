# TestPlan автоматизации тестирования сценария отправки заявки на вклад "Накопилка"

## Цель тестирования:
проверка возможности открытия вклада "Накопилка" в АО "Альфа-Банк"

**Перечень автоматизируемых сценариев:**

- переход на страницу вклада "Накопилка" с главной страницы
- переход на страницу вклада "Накопилка" со страницы "Вклады"
- переход на страницу вклада "Накопилка" по прямой ссылке
- переход на страницу отправки заявки с помощью кнопки "Заполнить заявку"
- переход на страницу отправки заявки с помощью ссылки "Копилка для сдачи"
- переход на страницу отправки заявки с помощью ссылки "Копилка для зарплаты"
- заполнение и отправка анкеты с помощью кнопки "Мы перезвоним"
- контроль поступления заявки на обратный звонок в систему

**Перечень используемых инструментов:**
- Java 11 язык для написания автотестов
- Gradle для сборки проекта, для управления подключенными зависимостями, а так же для генерации отчётов о тестировании
- JUnit 5 для написания и запуска тестов
- Git и GitHub для хранения кода
- Selenide чтобы протестировать GUI
- Lombok чтобы оптимизировать код автотестов
- Faker для генерации тестовых данных
- AppVeyor для визуального отображения статуса интеграции

**Перечень необходимых разрешений от банка:**
- разрешение на проведение тестирования

**Перечень и описание возможных рисков при автоматизации:**
- временные затраты могут превысить количество времени затраченного на ручное тестирование
- тестируемый функционал может быть в скором времени отключен, и трудозатраты будут неоправданы
- в случае обновления какого-либо из используемых инструментов, необходимо снова тратить ресурсы на актуализацию автотестов

**Перечень необходимых специалистов для автоматизации:**
- QA Automation engineer

**Интервальная оценка с учётом рисков (в часах):**
от 6 до 30
