# Отчёт о тестировании приложения "Precision"

## Краткое описание

Создано базовое приложение. Используется три переменные, типа double, для хранения исходных данных и итогового значения. Фактический результат работы приложения отличается от ожидаемого.

## Описание тестов

Выполнено дымовое тестирование приложения.

## Результаты

1. 100% не успешных тестов
2. Ссылка на баг-репорт https://github.com/pava-14/j1.2.2/issues/1

## Общие рекомендации

Использовать форматированный вывод итогового значения:

    System.out.format("totalBonus = %.1f%n", totalBonus);
    
