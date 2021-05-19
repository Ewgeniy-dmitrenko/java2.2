# Отчёт о тестировании Precision

## Краткое описание

19.05.2021 - 19.05.2021 было проведено функциональное тестирование приложения Precision.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [Неверный расчет общей суммы бонусов после добавления дополнительного](https://github.com/Ewgeniy-dmitrenko/java2.2/issues/1#issue-895249386)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* IntelliJ IDEA

В качестве тестовых данных использовался код из ДЗ 1.2:
* public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}


Тестирование производилось в следующем окружении:
* Windows 10 64X
* Java 11