# Отчёт о тестировании код Intellege IDEA

## Краткое описание

07/09/2021 - 09.09.2021 приложения Intellege IDEA.

На тестирование затрачено: 3 часа

В процессе тестирования использовались следующие артефакты*:
 [Тест кейс](https://docs.google.com/spreadsheets/d/16EsK3smbk2-jCz-ZH2_VIDxoBCgVlXKs/edit?usp=sharing&ouid=100465392313455888756&rtpof=true&sd=true)


В результате тестирования выявлены следующие дефекты:
[Выдает неверный расчет итогового значения при пополнении счёта VIP-клиента](https://github.com/BEZDNA12341/main/issues/1#issue-1046153965)

## Описание процесса тестирования


В качестве тестовых данных использовались данные:
* [Ссылка на источник]( https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md) 


public class Main {
public static void main(String[] args) {
int price = 2_000_000_000;
int count = 500_000_000;
int total = price + count;
System.out.println(total);
}
}

Ожидаемый результат: java intellege IDEA складывает всю сумму,и выдаёт ответ 2_000_500_000

Тестирование производилось в следующем окружении:

* Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz 2.70 GHz
  64-разрядная операционная система, процессор x64
  Windows 10 Домашняя для одного языка
  21H1
* openjdk version "11.0.11" 2021-04-20
  OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9)
  OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)