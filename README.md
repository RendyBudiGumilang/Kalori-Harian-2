# Kalori-Harian-2


#include<stdio.h>
#include<stdlib.h>  
#include<windows.h>

int main()
{  
		char a, b; 
		int c,d,e,f; // variable pilihan jika (if) 
		int  total = 0; // jumlah kalori
		awal:
		system ("cls"); // menghapus layar utama
		system ("color F3"); // warna pada layar
		printf ("[Selamat Datang di Kalkulator Kalori]\n"); // judul aplikasi 
		printf ("\n----------------------------\n"); 
		printf ("[Ayo Hitung Jumlah Asupan Kalori Harianmu Disini !]"); // deskripsi aplikasi
		printf ("\n----------------------------\n");
		printf ("[1] Mulai!\n"); 
		printf ("[2] Keluar!\n");
		printf("[3] Help\n");
		printf ("Your choice: \n");
		scanf ("%s", &a);
		{
			switch(a){
			case '1':
			// pilih mulai
				
			{
					kembali:
					system("cls");
					printf("Makanan Apa yang Telah Kamu Makan Hari Ini?");
					printf ("\n----------------------------\n");
					printf("\nBerikut adalah Sumber Karbohidrat yang Telah Kamu Konsumsi\n");
					printf ("----------------------------\n");
					printf("\n[1]Nasi");
					printf("\n[2]Kentang");
					printf("\n[3]Sagu");
					printf("\n[4]Ubi");
					printf("\n[5]Singkong");
					printf("\n[6]Roti");
					printf("\n[7]Jagung\n");
					printf("Silahkan Pilih Makananmu....\n");
					scanf("%s", &b );
					
						switch(b){
						case '1':
						system("cls");
						printf("Jumlah Kalori pada Nasi = 204 kkal");
						total = total + 204; // hitung kalori nasi
						break;
					
						case '2':
						system("cls");
						printf("Jumlah Kalori pada Kentang = 77 kkal");
						total = total + 77; // hitung kalori kentang
						break;
						
						case '3':
						system ("cls");
						printf("Jumlah Kalori pada Sagu = 353 kkal");
						total = total + 353; // hitung kalori sagu
						break;
					
						case '4':
						system ("cls");
						printf("Jumlah Kalori pada Ubi = 86 kkal");
						total = total + 86; // hitung kalori ubi
						break;
					
						case '5':
						system ("cls");
						printf("Jumlah Kalori pada Singkong = 159 kkal");
						total = total + 159; // hitung kalori singkong
						break;
					
						case '6':
						system("cls");
						printf("Jumlah Kalori pada Roti = 265 kkal");
						total = total + 265; // hitung kalori roti
						break;
								
						case '7':
						system("cls");
						printf("Jumlah Kalori pada Jagung = 365 kkal");
						total = total + 365; // hitung kalori jagung
						break;
    			
    					default:
						system("cls");
						printf("error input, silahkan masukan yang benar\n");
						getch();
						goto kembali;
						break;
					}
				printf("\n\nSilahkan Klik Apa Saja untuk Melanjutkan. . . ");
				getch();
    			
    			do 
    		
				{
					system("cls");
					printf("Makanan Apa yang Telah Kamu Makan Hari Ini?");
					printf ("\n----------------------------\n");
					printf("\n\nBerikut adalah Sumber Protein yang Telah Kamu Konsumsi\n");
					printf ("\n----------------------------\n");
					printf("\n[1]Udang");
					printf("\n[2]Ikan");
					printf("\n[3]Telur");
					printf("\n[4]Cumi-Cumi");
					printf("\n[5]Tahu");
					printf("\n[6]Tempe");
					printf("\n[7]Susu\n");
					printf("\nSilahkan Pilih Makananmu....\n");
					scanf("%d", &c );
					{
	
						if(c==1)
						{
							system("cls");
							printf("Jumlah Kalori pada Udang = 100 kkal");
							total = total + 100; // hitung kalori udang
						}
						
						if(c==2)
						{
							system("cls");
							printf("Jumlah Kalori pada Ikan = 205 kkal");
							total = total + 205; // hitung kalori ikan
						}	
						
						if(c==3)
						{
							system ("cls");
							printf("Jumlah Kalori pada Telur = 155 kkal");
							total = total + 155; // hitung kalori telur
						}
						
						if(c==4)
						{
							system ("cls");
							printf("Jumlah Kalori pada Cumi-Cumi = 158 kkal");
							total=total+158; // hitung kalori cumi-cumi
						}
						
						if(c==5)
						{
							system ("cls");
							printf("Jumlah Kalori pada Tahu = 76 kkal");
							total=total+76; // hitung kalori tahu
						}
						
						if(c==6)
						{			
							system("cls");
							printf("Jumlah Kalori pada Tempe = 192 kkal");
							total=total+192; // hitung kalori tempe
						}
						
						if(c==7)
						{
							system("cls");
							printf("Jumlah Kalori pada Susu = 42 kkal");
							total=total+42; // hitung kalori susu
						}
					}
				}
				while (c<1||c>7);
				printf("\n\nSilahkan Klik Apa Saja untuk Melanjutkan . . .");
				getch();
				
				do 
				
				{

					system("cls");
					printf("Makanan Apa yang Telah Kamu Makan Hari Ini? ");
					printf ("\n----------------------------\n");
					printf("\n\nBerikut adalah Sumber Lemak yang Telah Kamu Konsumsi\n");
					printf ("\n----------------------------\n");
					printf("\n[1]Keju");
					printf("\n[2]Mayones");
					printf("\n[3]Daging Babi");
					printf("\n[4]Daging Sapi");
					printf("\n[5]Daging Kambing");
					printf("\n[6]Daging Ayam");
					printf("\n[7]Minyak Kedelai/Jagung/Zaitun\n");
					printf("\nSilahkan Pilih Makananmu....\n");
					scanf("%d", &e );
					{	
		
						if(e==1)
						{
							system("cls");
							printf("Jumlah Kalori pada Keju = 403 kkal");
							total = total + 403; // hitung kalori keju
						}
						
						if(e==2)
						{
							system("cls");
							("Jumlah Kalori pada Mayones = 680 kkal");
							total=total+680; // hitung kalori mayones
						}
							
						if(e==3)
						{
							system ("cls");
							printf("Jumlah Kalori pada Daging Babi = 424 kkal");
							total=total+424; // hitung kalori daging babi
						}
						
						if(e==4)
						{
							system ("cls");
							printf("Jumlah Kalori pada Daging Sapi = 251 kkal");
							total=total+251; // hitung kalori daging sapi
						}
						
						if(e==5)
						{
							system ("cls");
							printf("Jumlah Kalori pada Daging Kambing = 143 kkal");
							total=total+143; // hitung kalori daging kambing
						}
						
						if(e==6)
						{
							system("cls");
							printf("Jumlah Kalori pada Daging Ayam = 239 kkal");
							total=total+239; // hitung kalori daging ayam
						}
						
						if(e==7)
						{
							system("cls");
							printf("Jumlah Kalori pada Minyak Kedelai/Jagung/Zaitun = 884 kkal");
							total=total+884; // hitung minyak kedelai/jagung/zaitun
						}
					}
				}
				while (e<1||e>7);
				printf("\n\nSilahkan Klik Apa Saja untuk Melanjutkan . . .");
				getch();	

				do 
				{

					system("cls");
					printf("Makanan Apa yang Telah Kamu Makan Hari Ini?");
					printf ("\n----------------------------\n");
					printf("\n\nBerikut adalah Sumber Mineral dan Vitamin yang Telah Kamu Konsumsi\n");
					printf ("\n----------------------------\n");
					printf("\n[1]Sayur Hijau");
					printf("\n[2]Hati Sapi");
					printf("\n[3]Buah Pisang");
					printf("\n[4]Buah Pepaya");
					printf("\n[5]Buah Apel");
					printf("\n[6]Buah Alpukat");
					printf("\n[7]Buah Jeruk");
					printf("\n[8]Buah Melon");
					printf("\n[9]Buah Semangka");
					printf("\nSilahkan Pilih Makananmu....\n");
					scanf("%d", &f );
	
					{

						if(f==1)
						{
							system("cls");
							printf("Jumlah Kalori pada Sayur Hijau = 41 kkal");
							total = total + 41; // hitung kalori sayur hijau
						}
						
						if(f==2)
						{
							system("cls");
							printf("Jumlah Kalori pada Hati Sapi = 165 kkal");
							total=total+165; // hitung kalori hati sapi
						}
							
						if(f==3)
						{
							system ("cls");
							printf("Jumlah Kalori pada Buah Pisang = 89 kkal");
							total=total+89; // hitung kalori buah pisang
						}
						
						if(f==4)
						{
							system ("cls");
							printf("Jumlah Kalori pada Buah Pepaya = 43 kkal");
							total=total+43; // hitung kalori buah pepaya
						}
						
						if(f==5)
						{
							system ("cls");
							printf("Jumlah Kalori pada Buah Apel = 52 kkal");
							total=total+52; // hitung kalori buah apel
						}
						
						if(f==6)
						{
							system("cls");
							printf("Jumlah Kalori pada Buah Alpukat = 160 kkal");
							total = total + 160; // hitung kalori buah alpukat
						}
						
						if(f==7)
						{
							system("cls");
							printf("Jumlah Kalori pada Buah Jeruk = 62 kkal");
							total=total+62; // hitung kalori buah jeruk
						}
						
						if(f==8)
						{
							system("cls");
							printf("Jumlah Kalori pada Buah Melon = 34 kkal");
							total=total+34; // hitung kalori buah melon
						}
						
						if(f==9)
						{
							system("cls");
							printf("Jumlah Kalori pada Buah Semangka = 30 kkal");
							total=total+30; // hitung kalori buah semangka
						}
					}
				}
				while (f<1||f>7);
				printf("\n\nSilahkan Klik Apa Saja untuk Melanjutkan . . .");
				getch();	

				system ("cls");
				printf ("\nTotal Kalori Yang Masuk Ke Tubuh Kamu Sebesar : \n%d Kkal\n\n", total); 
				printf("\nTotal Kalori yang Disarankan Oleh Para Ahli untuk Laki-Laki adalah 600  kKal dalam Sekali Makan atau 1800 kKal dalam Satu Hari\n");
				printf("\ndan untuk Perempuan adalah sebesar 425 dalam Sekali Makan atau 1250 kKal Setiap Harinya\n");
				getch();

				system ("cls");
				main();
			}
			break;

			case '2':
				// pilih keluar
			{
				system("cls");
				printf("\nTerima Kasih Sudah Menggunakan Program ini:)\n");
				exit(0);
			}
			break;

			case '3':
				// pilih help
			{
				system ("cls");
				printf("\nKalkulator Kalori adalah program yang dibuat untuk mempermudah perhitungan jumlah kalori harian yang Anda.\n");
				printf("\nProgram ini telah menyimpan jumlah kalori dari setiap jenis makanan yang Anda Konsumsi.\n");
				printf("\nJumlah kalori yang tertera telah disesuaikan dengan jumlah takaran 1 porsi makan.\n");
				printf("\nUntuk melakukan perhitungan Anda cukup memilih makanan apa saja yang telah Anda Konsumsi.\n");
				printf("\nAnda juga akan mengetahui jumlah kalori dari setiap jenis makanan yang anda pilih.\n");
				printf("\nSelamat Mencoba !\n");
				getch();
				main();
			}
			break;
			
			default:
			system("cls"); // menghapus layar
			printf("error input, silahkan masukan yang benar\n");
			getch();
			goto awal; // kembali ke awal
			break;
		}
	}
	return 0;
	}
