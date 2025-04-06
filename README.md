import java.util.Arrays;

public class Main {
    public static void main(String[] args) {
        int[] numbers = {3, 5, 1, 4, 2, 6, 9, 7, 8, 10, 12, 11};
        Arrays.sort(numbers); // Сортируем массив

        // Вывод отсортированного массива
        System.out.println("Отсортированный массив: " + Arrays.toString(numbers));
    }
}
