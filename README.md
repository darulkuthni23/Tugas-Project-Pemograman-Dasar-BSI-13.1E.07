Toko Coffe Breaker Why :
Darul Kuthni
Nanang Hidayat
Salim Zulkarnaen


#include <stdio.h>
#include <conio.h>
#include <iostream.h>
main (void)
{
 ulang:
 int kdukuran, total, jumbel, bayar, kembali, harga;
 char kdproduk, melang;

printf("\n");
printf("\n");
cout<<"                       Toko Coffe Breaker Why                      ";
cout<<"                 Telp:085814941691 Kode Pos: 11420                     ";
printf("\n");
printf("================================================================\n");
printf("\n");

printf("*****[PILIHAN PRODUK]*****\n");
printf("A. Coffe Latte\n");
printf("    1. Ukuran Kecil  = 15000\n");
printf("    2. Ukuran Sedang = 20000\n");
printf("    3. Ukuran Besar  = 25000\n");
printf("B. Coffe Capucino\n");
printf("    1. Ukuran Kecil  = 13500\n");
printf("    2. Ukuran Sedang = 17500\n");
printf("    3. Ukuran Besar  = 20000\n");
printf("C. Coffe Mochacino\n");
printf("    1. Ukuran Kecil  = 15000\n");
printf("    2. Ukuran Sedang = 16500\n");
printf("    3. Ukuran Besar  = 22000\n");
printf("D. Coffe Caramelo\n");
printf("    1. Ukuran Kecil  = 19000\n");
printf("    2. Ukuran Sedang = 23000\n");
printf("    3. Ukuran Besar  = 30000\n");
printf("E. Coffe Huzelnut\n");
printf("    1. Ukuran Kecil  = 13500\n");
printf("    2. Ukuran Sedang = 19900\n");
printf("    3. Ukuran Besar  = 22900\n");
printf("============================\n");
printf("Kode Produk (A..E) :"); scanf("%s", &kdproduk);
printf("Kode Ukuran (1..3) :"); scanf("%d", &kdukuran);
printf("============================\n");
switch (kdproduk)

   {
   case 'a':
   case 'A':
    if (kdukuran == 1){
     printf("Jenis Produk        = Coffe Latte \n");
     printf("Ukuran              = kecil \n");
     printf("Harga               = 15000");
     harga = 15000;}
    else if (kdukuran == 2){
     printf("Jenis Produk        = Coffe Latte \n");
     printf("Ukuran              = Sedang \n");
     printf("Harga               = 20000 \n");
     harga = 20000;}
    else if (kdukuran == 3){
     printf("Jenis Produk        = Coffe Latte \n");
     printf("Ukuran              = Besar \n");
     printf("Harga               = 25000 \n");
     harga = 25000;}
    break;

   case 'b':
   case 'B':
    if (kdukuran == 1){
     printf("Jenis Produk        = Coffe Capucino \n");
     printf("Ukuran              = kecil \n");
     printf("Harga               = 13500 \n");
     harga = 13500;}
    else if (kdukuran == 2){
     printf("Jenis Produk        = Coffe Capucino \n");
     printf("Ukuran              = Sedang \n");
     printf("Harga               = 17500 \n");
     harga = 17500;}
    else if (kdukuran == 3){
     printf("Jenis Produk        = Coffe Capucino \n");
     printf("Ukuran              = Besar \n");
     printf("Harga               = 20000 \n");
     harga = 20000;}
    break;

   case 'c':
   case 'C':
    if (kdukuran == 1){
     printf("Jenis Produk        = Coffe Mochacino \n");
     printf("Ukuran              = kecil \n");
     printf("Harga               = 15000 \n");
     harga = 15000;}
    else if (kdukuran == 2){
     printf("Jenis Produk        = Coffe Mochacino \n");
     printf("Ukuran              = Sedang \n");
     printf("Harga               = 16500 \n");
     harga = 16500;}
    else if (kdukuran == 3){
     printf("Jenis Produk        = Coffe Mochacino \n");
     printf("Ukuran              = Besar \n");
     printf("Harga               = 22000 \n");
     harga = 22000;}
    break;

    case 'd':
   case 'D':
    if (kdukuran == 1){
     printf("Jenis Produk        = Coffe Caramelo \n");
     printf("Ukuran              = kecil \n");
     printf("Harga               = 19000 \n");
     harga = 15000;}
    else if (kdukuran == 2){
     printf("Jenis Produk        = Coffe Caramelo \n");
     printf("Ukuran              = Sedang \n");
     printf("Harga               = 23000 \n");
     harga = 16500;}
    else if (kdukuran == 3){
     printf("Jenis Produk        = Coffe Caramelo \n");
     printf("Ukuran              = Besar \n");
     printf("Harga               = 30000 \n");
     harga = 22000;}
    break;

    case 'e':
   case 'E':
    if (kdukuran == 1){
     printf("Jenis Produk        = Coffe Huzelnut \n");
     printf("Ukuran              = kecil \n");
     printf("Harga               = 13500 \n");
     harga = 15000;}
    else if (kdukuran == 2){
     printf("Jenis Produk        = Coffe Huzelnut \n");
     printf("Ukuran              = Sedang \n");
     printf("Harga               = 19900 \n");
     harga = 16500;}
    else if (kdukuran == 3){
     printf("Jenis Produk        = Coffe Huzelnut \n");
     printf("Ukuran              = Besar \n");
     printf("Harga               = 22900 \n");
     harga = 22000;}
    break;
    default:
    printf("maaf... kode yang anda masukan salah atau tidak terdaftar \n");


  printf("Apakah Anda Ingin Mengulanginya Lagi [Y/T] ???") ; scanf("%s", &melang);
  if(melang=='y' || melang=='Y'){goto ulang;} else
  if(melang=='t' || melang=='T'){goto selesai;}
 break ;
   }

printf ("Masukan Jumlah Beli = "); scanf("%d", &jumbel);
total = harga * jumbel;
printf ("Total Bayar         = %d \n",total);
printf ("Uang Bayar          = "); scanf("%d", &bayar);
kembali = bayar - total ;
printf ("Uang Kembali        = %d \n", kembali);
printf("============================\n");
printf ("***** Terima Kasih ***** \n");
printf("\n");
printf("Apakah Anda Ingin Mengulanginya Lagi [Y/T] ???") ; scanf("%s", &melang);
  if(melang=='y' || melang=='Y'){goto ulang;} else
  if(melang=='t' || melang=='T'){goto selesai;}

selesai: ;

getch();

}
