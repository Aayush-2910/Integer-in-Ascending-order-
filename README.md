# Integer-in-Ascending-order-
Sort array in ascending order 

import java.util.Arrays;

public class SortArray {
    public static void main(String[] args) {
        int[] numbers = {5, 2, 8, 3, 1, 9, 4};

        System.out.println("Original array:");
        System.out.println(Arrays.toString(numbers));

        // Sorting the array in ascending order
        Arrays.sort(numbers);

        System.out.println("Sorted array in ascending order:");
        System.out.println(Arrays.toString(numbers));
    }
}
