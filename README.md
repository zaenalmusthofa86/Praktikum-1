# Praktikum_1


# Latihan pertama (Membuat perhitungan Luas persegi panjang)
```
-Mendeklarasikan variabel int p,l sebagai variabel input dan variabel L sebagai variabel hasil
-Menghitung luas dengan rumus L = p*l
-Menampilkan hasilnya kelayar << cout" hasilnya adalah : " << L << endl;
-Beriut code lengkapnya:

int main()
	{
    	   int p, l, L;
           p= 8;
           l= 6;
           L= p*l;
           cout<< "Luasnya adalah :" << L << endl;
	}
```
-Berikut Screenshotnya:

![img](https://github.com/zaenalmusthofa86/Praktikum-1/blob/master/Latihan1.png)

# Latihan kedua (Membuat penentuan bilagan ganjil dan genap)
```
-Mendeklariskan variabel int x sebagai variabel input
-Memasukan nilai x
-Menentukan nilai genap dan ganjil dengan rumus if (x%2==0)
	penjelasanya #jika nilai x dibagi dengan 2 hasilnya 0 maka bilangan itu adalah genap, dan jika tidak hasilnya ganjil
-Menampilkan hasilnya ke layar dengan kode
	cout<<" Bilangan yang anda masukkan adalah Genap";
	 else
	 cout<<"Bilangan yang anda masukan adalah Ganjil";
-Berikut kode lengkapnya:

int main()
	{
  	  int x;
  	  cout << "Masukan Bilangan :"<< endl;
 	  cin>>x;
    	  if (x%2==0)
   	  cout<<" Bilangan yang anda masukkan adalah Genap";
          else
    	  cout<<"Bilangan yang anda masukan adalah Ganjil";
    	  return 0;
	}
```
-Berikut Screenshotnya:

![img](https://github.com/zaenalmusthofa86/Praktikum-1/blob/master/Latihan2.png)

# Latihan Ketiga (Menentukan nilai terbesar dan terkecil dari nilai yang di input)
```
-Mendeklarasikan variabel int i untuk pembatasan inputan, variabel n,nilai untuk inputan
-Variabel max,min untuk pembatasan nilai
-Membuat perintah for i untuk menentukan banyak nilai yang akan dibandingkan
 for (i=2;i<=n;i++)
	penjelasannya 
*Dimana i akan membaca pada inputan kedua dan i kurang dari sama dengan inputan n dan nilai i akan menambah satu.
-Menggunakan perintah if untuk menentukan nilai terbesar dan terkecil
 if (nilai>max) max=nilai;
 if (nilai<min) min=nilai;
	penjelasanya
*Jika inputan nilai lebih dari max maka terbesar lah hasilnya.
*Jika inputan nilai kurang dari min maka terkecil lah hasilnya
-Menampilkan hasilnya kelayar dengan kode
	cout << "Nilai Terbesar adalah:" <<max<< "\nNilai Terkecil adalah:"<<min<< endl;
-Berikut kode lengkapnya:

int main()
		{
   		   int i,n,max,min,nilai;

   		   cout<<"=====Mencari Bilangan Terbesar & Terkecil==== \n";
   		   cout<<"Masukan Banyak data :";
   		   cin>> n;
  		   cout<< "Masukan Nilai :";
  		   cin>> nilai;

  		   max=nilai;
   		   min=nilai;

   		   for(i=2;i<=n;i++){
   		   cout<<"Masukan Nilai :";
   		   cin>>nilai;
    		   if (nilai>max) max=nilai;
    		   if (nilai<min) min=nilai;
   		}
    		  cout << "Nilai Terbesar adalah:" <<max<< "\nNilai Terkecil adalah:"<<min<< endl;
   		 return 0;
```
-Berikut Screenshotnya:

![img](https://github.com/zaenalmusthofa86/Praktikum-1/blob/master/Latihan3.png)
 
# Latihan Keempat (Membuat perulangan penjumlahan)
```
-Mendeklarasikan variabel int x sebagai batasan inputan nilai
-Mendeklarasikan variabel nilai,bil sebagai inputan
-Mendeklarasikan total sebagai variabel hasil
-Membuat pembatasan perulangan untuk inputan nilai yang akan dijumlahkan dengan rumus for
	for (x=1;x<=nilai;x++)
penjelasanya
	x akan membaca saat inputan ke 1 dimana x kurang dari sama dengan inputan nilai dan x akan bertambah 1
-Menjumlahkan nilai yang diinput pada nilai bil dengan rumus
	total=total+bil;
-Menampilkan hasilnya kelayar cout<<"\ntotal="<<total;
-Berikut kode lengkapnya:

int main()
		{
 		   int x,nilai, bil, total=0;
                   cout<< "Masukan Jumlah Nilai Yang Akan Di input =";
		   cin>> nilai;
 		   for (x=1;x<=nilai;x++)
 			{
     			  cout<<"Masukan Nilai ke " <<x<<"=";
     			  cin>>bil;
     			  total=total+bil;
    			  cout<<"\ntotal="<<total;
 			}
   		   return 0;
		}
```
-Berikut Screenshotnya:

![img](https://github.com/zaenalmusthofa86/Praktikum-1/blob/master/Latihan4.png)

