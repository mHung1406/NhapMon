import java.util.Scanner;

public class NhapDiem {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Nhập số môn: ");
        int n = sc.nextInt();
        double tong = 0;
        
        for (int i = 0; i < n; i++) {
            System.out.print("Điểm môn " + (i + 1) + ": ");
            tong += sc.nextDouble();
        }
        
        System.out.println("Điểm TB: " + (tong / n));
        sc.close();
    }
}
# NhapMon
