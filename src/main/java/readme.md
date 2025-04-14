Запуск тестов

1.Тесты находятся в классах:

    1.src/test/java/e2e/CheckoutTest.java
    2.src/test/java/tests/SaucedemoLoginTest.java


2.Выделить правой кнопкой классы с тестами и выбрать Run
3.Тесты запускаются в браузере Chrome (должен быть установлен локально)
4.Видим прохождение тестов в браузере (headful mode)
5.Результаты для allure сохраняются в папку target/allure-results


Формирование отчета:

1.В терминале выполнить:
2. cd target
3. allure generate //HTML-отчет сформируется в target/allure-report
4. allure open
   Будет открыт отчет в браузере по умолчанию