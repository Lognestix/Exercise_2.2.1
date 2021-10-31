# Код Java находящийся в этом репозитории

```Java
public class Main {
    public static void main(String[] args) {
        BonusMilesService service = new BonusMilesService();
        int price = 10_000;
        int miles = service.calculate(price);
        System.out.println(miles);
    }
}
```
```Java
public class BonusMilesService {
    public int calculate(int price) {
        int bonus = price / 20;       //Расчет бонусных миль
        return (bonus);
    }
}
```