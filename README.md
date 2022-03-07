# Taksimetre Hesaplayan Program
Patika.dev > Java101 > Temel Kavramlar ve Değişkenler > Pratik4 - Taksimetre Hesaplayan Program

## Java ile gidilen mesafeye (KM) göre taksimetre tutarını ekrana yazdıran programı yazın.

- Taksimetre KM başına 2.20 TL tutmaktadır.
- Minimum ödenecek tutar 20 TL'dir. 20 TL altında ki ücretlerde yine 20 TL alınacaktır.
- Taksimetre açılış ücreti 10 TL'dir.

		import java.util.*;
		
		public class pratik2 {

			public static void main(String[] args) {
			
				// Yeni bir tarayıcı(scanner) oluştur.
				Scanner sc = new Scanner(System.in);
		
				// Kullanıcıdan km değerini al.
				System.out.println("Km girin: ");
				int km = sc.nextInt();
		
				// Tutar hesaplayan formülü oluştur.
				double tutar = 10 + (km * 2.20);
		
				// Koşulları oluştur.
				if (tutar <= 20)
					System.out.println("Ödenecek tutar: 20 TL.");
				else
					System.out.println("Ödenecek tutar: " + tutar + " TL.");
		
			}
		}
