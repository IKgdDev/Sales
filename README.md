# Менеджер продаж

*Позволяет автоматизировать работу отдела продаж.*

**Возможности:**

1. Производит анализ статистики продаж, 
и определяет максимальное количество продаж

```java
public int max() {
        int max = -1;
        for (int sale : sales) {
            if (sale > max) {
                max = sale;
            }
        }
        return max;
    }
```




