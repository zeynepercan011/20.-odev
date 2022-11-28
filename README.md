# 20.-odev

//maksimum say�y� bulma

#include<stdio.h>

int maksimum(int x , int y , int z);

int main(void)
{
	int sayi1,sayi2,sayi3;
	
	printf("sayilari giriniz: \n");
	scanf("%d%d%d" , &sayi1,&sayi2,&sayi3);
	
	int sonuc=maksimum(sayi1,sayi2,sayi3);
	printf("sonuc: %d \n" , sonuc);
	
	return 0;
}

int maksimum(int x , int y , int z)
{
	int maks=x;
	
	if(y>x)
	maks=y;
	
	if(z>maks)
	maks=z;
	
	return maks;
}
