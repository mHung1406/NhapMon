import java.util.Scanner;
public class SumSeries {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Nhập giá trị N: ");
        int N = scanner.nextInt();
        int sum = 0;

        for (int i = 1; i <= N; i++) {
            int num = Integer.parseInt(i + "" + i);
            sum += num;
        }
        System.out.println("Tổng S = " + sum);
        scanner.close();
    }
}

