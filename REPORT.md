# Отчёт о тестировании Precision

## Краткое описание

**14.07.2021 - 14.07.2021** было проведено функциональное тестирование дополнительного приложения начисления бонуса клиентам.

На тестирование затрачено: **1 час**


**В результате тестирования выявлены следующие дефекты:**   

![Скриншот](https://user-images.githubusercontent.com/46699662/125649781-652950e7-b5c2-42ab-bd63-d31a37327407.png)

[Ссылка на Issues](https://github.com/alexboom85/Precision/issues/1)

## Описание процесса тестирования**
1. Открываем программу Intellij IDЕА   
2. Вводим код

        public class Main {
          public static void main(String[] args) {
            double regularBonus = 0.3;
            double specialBonus = 0.6;
            double totalBonus = regularBonus + specialBonus;
              System.out.println(totalBonus);
          }
        }
        
3. Жмем Run
4. Смотрим результат компилятора

**В качестве тестовых данных использовались данные: условия задания [Задание](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)**  

*ОР: В результате компилятор получается число 0.9    
ФР:  В результате компилятор выдает число 0.89999999999*    

**Тестирование производилось в следующем окружении:**   
*Ноутбук HP Pavilion,Windows 10, x64*    
*Openjdk version "11.0.11" 2021-04-20*  
