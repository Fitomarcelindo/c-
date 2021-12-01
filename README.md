# c-
Porgram pembayaran UKT |C++|
#include<iostream>
using namespace std;

int main(){
	string kode,jurusan,ulang;
	long spp,biaya,total;
	spp = 8000000;
	biaya = 1100000;
	
	do{
	cout<<"===================================================="<<endl;
	cout<<"==SELAMAT DATANG SILAHKAN LAKUKAN PEMABYARAN ANDA=="<<endl;	
	cout<<"===================================================="<<endl;
	
	cout<<"pilih jurusan 	: "<<endl;
	cout<<"TE : TEKNIK ELEKTRO "<<endl;
	cout<<"TM : TEKNIK MESIN "<<endl;
	cout<<"TI : TEKNIK INFORMATIKA"<<endl;
	cout<<"TS : TEKNIK SIPIL"<<endl;
	cout<<"===================================================="<<endl;
	
	cout<<"masukan kode jurusan [TE,TM,TI,TS] = ";
	cin>>kode;
	
	
		if(kode== "TE"){
		jurusan = "TEKNIK ELEKTRO";
		jurusan = "TEKNIK ELEKTRO";
		cout<<"		TEKNIK ELEKTRO		"<<endl;
		cout<<"masukan jumlah biaya UP \t = ";
		cin>>biaya;
		cout<<"masukan jumlah spp \t\t = ";
		cin>>spp;
		cout<<"----------------------------------"<<endl;
		total = spp+biaya;
		cout<<"total \t  = ";
		
	}
	if(kode== "TM"){
		jurusan = "TEKNIK MESIN";
		jurusan = "TEKNIK MESIN";
		cout<<"		TEKNIK MESIN		"<<endl;
		cout<<"masukan jumlah biaya UP \t = ";
		cin>>biaya;
		cout<<"masukan jumlah spp \t\t = ";
		cin>>spp;
		cout<<"----------------------------------"<<endl;
		total = spp+biaya;
		cout<<"total \t  = ";
	}
	if(kode== "TI"){
		jurusan = "TEKNIK INFORMATIKA";
		jurusan = "TEKNIK INFORMATIKA";
		cout<<"		TEKNIK INFORMATIKA		"<<endl;
		cout<<"masukan jumlah biaya UP \t = ";
		cin>>biaya;
		cout<<"masukan jumlah spp \t\t = ";
		cin>>spp;
		cout<<"----------------------------------"<<endl;
		total = spp+biaya;
		cout<<"total \t  = ";
	}
	if(kode== "TS"){
		jurusan = "TEKNIK SIPIL";
		jurusan = "TEKNIK SIPIL";
		cout<<"		TEKNIK SIPIL	"<<endl;
		cout<<"masukan jumlah biaya UP \t = ";
		cin>>biaya;
		cout<<"masukan jumlah spp \t\t = ";
		cin>>spp;
		cout<<"----------------------------------"<<endl;
		total = spp+biaya;
		cout<<"total \t  = ";
	}
	else{
		jurusan = "anoynmous";
	}
	
	cout<<"biaya + sppp = "<<total<<endl;
	cout<<"================================"<<endl;
	
	cout<<"apakah anda ingin pembayar lagi (Y : T) : ";
	cin>>ulang;
	}while(ulang== "Y");
	
	cout<<"terima kasih :) ";
	
}
