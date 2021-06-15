# PatikaDevJava101pratik2
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
			System.out.println("Ödenecek tutar: " + tutar + " TL.");;
		
	}

}
