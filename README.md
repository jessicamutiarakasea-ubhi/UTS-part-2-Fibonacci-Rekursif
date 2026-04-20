1. Import Library
    import java.util.Scanner;
   (Digunakan untuk mengambil input dari pengguna melalui keyboard.)

2. Deklarasi Class
   public class FibonacciRekursif {
   (Mendefinisikan kelas utama dengan nama FibonacciRekursif sebagai tempat seluruh program.)

3. Fungsi Rekursif Fibonacci
      public static int fibonacci(int n) {
    (Method ini digunakan untuk menghitung nilai Fibonacci ke-n.)

    >>Kondisi dasar (base case)          
          if (n == 0) {
      return 0;
  } else if (n == 1) {
      return 1;
  }
   (jika
    n = 0 → hasil = 0
     n = 1 → hasil = 1
     agar rekursi berhenti.)
    
    >>Proses rekursif
        else {
    return fibonacci(n - 1) + fibonacci(n - 2);
}
      Menghitung nilai Fibonacci dengan menjumlahkan:suku sebelumnya (n-1) dan dua langkah sebelumnya (n-2)


 4. Method Utama (main)
     public static void main(String[] args) {
     (Tempat program mulai dijalankan.)


 5. Membuat Objek Scanner
     Scanner input = new Scanner(System.in);
     (Digunakan untuk membaca input dari user.)

     
6. Input dari User
   System.out.print("Masukkan jumlah suku Fibonacci: ");
int n = input.nextInt();
(Menampilkan pesan ke layar dan Menyimpan jumlah suku Fibonacci yang ingin ditampilkan ke variabel n)


7. Menampilkan Judul Output
   System.out.println("Deret Fibonacci hingga suku ke-" + n + " adalah:");
   (Menampilkan teks penjelas sebelum deret Fibonacci dicetak.)


8. Perulangan untuk Menampilkan Deret
      for (int i = 0; i < n; i++) {
      (Loop dari 0 sampai n-1 untuk mencetak setiap suku Fibonacci.)

9.Menampilkan Nilai Fibonacci
  System.out.print(fibonacci(i));
  (Memanggil fungsi rekursif untuk setiap nilai i lalu mencetak hasilnya.)

  10. Format Koma
      if (i < n - 1) {
    System.out.print(", ");
    }
(Menambahkan tanda koma hanya jika belum di elemen terakhir, supaya tidak ada koma di akhir.)

11. Menutup Scanner
    input.close();
(Menutup input untuk menghindari kebocoran resource.)

                                                                            Kesimpulan :
                                                                                        1.Program menerima input jumlah suku (n)
                                                                                        2.Menggunakan rekursif untuk menghitung Fibonacci
                                                                                        3.Menggunakan loop untuk menampilkan deret
                                                                                        4.Output diformat dengan koma agar rapi



      
     
   
