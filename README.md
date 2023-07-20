# Question-nine
public class SumBetweenNumbers {
    public static void main(String[] args) {
        int start = 20;
        int end = 25;
        int sum = 0;
        int currentNumber = start;

        do {
            sum += currentNumber;
            currentNumber++;
        } while (currentNumber <= end);

        System.out.println("The sum of numbers between " + start + " and " + end + " is: " + sum);
    }
}
