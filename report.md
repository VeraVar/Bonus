# Отчёт о тестировании приложения "Bonus"

## Краткое описание
Проверена работоспособность кода для расчёта бонуса:
'''
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
'''
Обнаружено, что при расчёте бонуса неверно отображается итоговое значение.
Фактический результат, выведенный программой, равен 0.8999999999999999. Ожидаемый результат 0.9. 

## Описание тестов

Проведено позитивное функциональное тестирование (тестировалась функция корректного расчёта итогового значения бонуса).

## Результаты

1. 100% не успешных тестов
2. Ссылка на баг-репорт: https://github.com/VeraVar/Bonus/issues/1

## Общие рекомендации

По итогам тестирования можно рекомендовать доработать код.