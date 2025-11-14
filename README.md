# kasir_java
“Aplikasi kasir sederhana berbasis Java yang memungkinkan pengguna memasukkan nama barang, harga, dan jumlah untuk menghitung total pembayaran. Project ini dibuat untuk melatih dasar Java seperti input, variabel, dan perhitungan dasar dalam program console.”
import java.util.Scanner;

public class KasirSederhana {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        System.out.print("Nama Barang: ");
        String barang = input.nextLine();
        
        System.out.print("Harga Barang: ");
        int harga = input.nextInt();
        
        System.out.print("Jumlah Barang: ");
        int jumlah = input.nextInt();
        
        int total = harga * jumlah;
        
        System.out.println("\n=== STRUK PEMBELIAN ===");
        System.out.println("Barang : " + barang);
        System.out.println("Harga  : " + harga);
        System.out.println("Jumlah : " + jumlah);
        System.out.println("Total  : " + total);
    }
}
