В проекті має бути реалізовано функціонал виведення інформації про споживача (Customer).
Виведення має бути таким:

Customer: Tom, phone 555 123-8596

(1) Cтворіть проект Customer на локальній машині через IntelliJ IDEA (IDE).

(2) Структура проекту має бути такою:

(3) Доопрацюйте функціонал класу Customer

package app;

public class Customer {

    // Виправте декларацію змінних класу
    private final name;
    private final String phone;

    // Виправте визначення конструктора
    public Customer(name, String ) {
        this.name = name;
        this.phone = phone;
    }

    // Пропишіть нижче getters для всіх змінних класу

}

(4) Доопрацюйте функціонал класу Main

package app;

// Виправте цей клас
public class Main {

    public static void main(String[] args) {
        Customer customer = getCustomer(getData());
        String output = "Customer: ".getName() +
                ", phone " + customer.getPhone();
        getOutput(output);
    }

    public static String[] getData() {
        return new String[]{/* пропишіть значення для об'єкту Customer*/};
    }

    public static Customer getCustomer(String[] data) {
        return new Customer(data[0], data[1]);
    }

    public static void getOutput(String output) {
        System.out.println(output);
    }
}

(5) Залийте виконаний проект на свій GitHub репозиторій, посилання на який зазначте в LMS.