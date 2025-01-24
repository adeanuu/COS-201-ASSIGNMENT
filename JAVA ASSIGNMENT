# COS-201-ASSIGNMENT
public class NigerianFlag {
    public static void main(String[] args) {
        String green = "GREEN ";
        String white = "WHITE ";

        // The flag has three vertical stripes: green, white, green
        for (int i = 0; i < 9; i++) {
            if (i % 3 == 1) {
                System.out.print(white);
            } else {
                System.out.print(green);
            }
            // Print a new line after every third character
            if (i % 3 == 2) {
                System.out.println();
            }
        }
    }
}
Using a Nested Loop
java
public class NigerianFlagNested {
    public static void main(String[] args) {
        String green = "GREEN ";
        String white = "WHITE ";

        for (int i = 0; i < 3; i++) { // Number of rows
            for (int j = 0; j < 3; j++) { // Number of columns
                if (j == 1) {
                    System.out.print(white);
                } else {
                    System.out.print(green);
                }
            }
            System.out.println(); // Move to the next line after each row
        }
    }
}
# question 2
import java.util.Arrays;

public class Statistics {
    public static void main(String[] args) {
        int[] data = {2, 5, 5, 9, 4, 7, 0, 9, 6, 11, 12};
        int n = data.length;

        // Calculate the mean
        double mean = calculateMean(data, n);
        System.out.println("Mean: " + mean);

        // Calculate the median
        double median = calculateMedian(data, n);
        System.out.println("Median: " + median);

        // Calculate the standard deviation
        double standardDeviation = calculateStandardDeviation(data, n, mean);
        System.out.println("Standard Deviation: " + standardDeviation);
    }

    public static double calculateMean(int[] data, int n) {
        double sum = 0;
        for (int value : data) {
            sum += value;
        }
        return sum / n;
    }

    public static double calculateMedian(int[] data, int n) {
        Arrays.sort(data);
        if (n % 2 == 0) {
            return (data[n / 2 - 1] + data[n / 2]) / 2.0;
        } else {
            return data[n / 2];
        }
    }

    public static double calculateStandardDeviation(int[] data, int n, double mean) {
        double sumSquaredDifferences = 0;
        for (int value : data) {
            sumSquaredDifferences += Math.pow(value - mean, 2);
        }
        return Math.sqrt(sumSquaredDifferences / n);
    }
}
# question 3
import java.util.Scanner;

public class UserInputArray {
    public static void main(String[] args) {
        int[] array = new int[10];
        Scanner scanner = new Scanner(System.in);

        // Accepting input from the user
        for (int i = 0; i < array.length; i++) {
            System.out.println("Enter the value for index " + i + ": ");
            array[i] = scanner.nextInt();
        }

        // Printing out the input using a for-each loop
        System.out.println("The elements you entered are: ");
        for (int value : array) {
            System.out.println(value);
        }

        scanner.close();
    }
}
# question 4
   public static void main(String[] args) {
        int[][] array = new int[10][10];
        Scanner scanner = new Scanner(System.in);

        // Accepting input from the user
        for (int i = 0; i < 10; i++) {
            for (int j = 0; j < 10; j++) {
                System.out.println("Enter the value for index (" + i + "," + j + "): ");
                array[i][j] = scanner.nextInt();
            }
        }

        // Printing out the input using a for-each loop
        System.out.println("The elements you entered are: ");
        for (int[] row : array) {
            for (int value : row) {
                System.out.print(value + " ");
            }
            System.out.println();
        }

        scanner.close();
    }
}
