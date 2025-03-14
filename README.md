## Task1
import java.util.Scanner;

public class FahrenheitToCelsius {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Ask user for temperature in Fahrenheit
        System.out.print("Enter temperature in Fahrenheit: ");
        double fahrenheit = scanner.nextDouble();

        // Convert to Celsius
        double celsius = (fahrenheit - 32) * 5 / 9;

        // Display result
        System.out.println("Temperature in Celsius: " + celsius);

        scanner.close();
    }
}
