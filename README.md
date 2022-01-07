#include<iostream>
using namespace std;

int main(){
	string kode,jurusan,ulang;
	long spp,biaya,total,uang,pay,back;
	spp = 8000000;
	biaya = 1100000;
	
	do{
	system("cls");
	cout<<"===================================================="<<endl;
	cout<<"	SELAMAT DATANG SILAHKAN LAKUKAN PEMABYARAN ANDA	"<<endl;	
	cout<<"===================================================="<<endl;
	
	cout<<" ilih jurusan 	: "<<endl;
	cout<<" TE : TEKNIK ELEKTRO "<<endl;
	cout<<" TM : TEKNIK MESIN "<<endl;
	cout<<" TI : TEKNIK INFORMATIKA"<<endl;
	cout<<" TS : TEKNIK SIPIL"<<endl;
	cout<<"===================================================="<<endl;
	
	cout<<" Masukkan kode jurusan [TE,TM,TI,TS] = ";
	cin>>kode;
	
	
		if(kode== "TE"){
		jurusan = "TEKNIK ELEKTRO";
		jurusan = "TEKNIK ELEKTRO";
		cout<<"		TEKNIK ELEKTRO		"<<endl;
		cout<<" Masukan jumlah biaya UP \t = Rp. ";
		cin>>biaya;
		cout<<" Masukan jumlah spp \t\t = Rp. ";
		cin>>spp;
		cout<<"----------------------------------"<<endl;
		total = spp+biaya;
		cout<<" Total \t  = Rp. "<<total<<endl;
		cout<<" Masukkan jumlah uang anda : Rp.";
		cin>>uang;
		back =  uang - total;
		cout<<" uang kemablian anda : Rp. "<<back<<endl;
		
		
	}
	if(kode== "TM"){
		jurusan = " TEKNIK MESIN";
		jurusan = " TEKNIK MESIN";
		cout<<"		TEKNIK MESIN		"<<endl;
		cout<<" Masukan jumlah biaya UP \t = Rp. ";
		cin>>biaya;
		cout<<" Masukan jumlah spp \t\t = Rp. ";
		cin>>spp;
		cout<<"----------------------------------"<<endl;
		total = spp+biaya;
		cout<<" Total \t  = Rp. "<<total<<endl;
		cout<<" Masukkan jumlah uang anda : Rp.";
		cin>>uang;
		back =  uang - total;
		cout<<" uang kemablian anda : Rp. "<<back<<endl;
		
	}
	if(kode== " TI "){
		jurusan = " TEKNIK INFORMATIKA";
		jurusan = " TEKNIK INFORMATIKA";
		cout<<"		TEKNIK INFORMATIKA		"<<endl;
		cout<<" Masukan jumlah biaya UP \t = p. ";
		cin>>biaya;
		cout<<" Masukan jumlah spp \t\t = Rp. ";
		cin>>spp;
		cout<<"----------------------------------"<<endl;
		total = spp+biaya;
		cout<<" Total \t  = Rp. "<<total<<endl;
		cout<<" Masukkan jumlah uang anda : Rp.";
		cin>>uang;
		back =  uang - total;
		cout<<" Uang kemablian anda : Rp. "<<back<<endl;
		
	}
	if(kode== "TS"){
		jurusan = "TEKNIK SIPIL";
		jurusan = "TEKNIK SIPIL";
		cout<<"		TEKNIK SIPIL	"<<endl;
		cout<<"masukan jumlah biaya UP \t = Rp. ";
		cin>>biaya;
		cout<<"masukan jumlah spp \t\t = Rp.";
		cin>>spp;
		cout<<"----------------------------------"<<endl;
		total = spp+biaya;
		cout<<" Total \t  = Rp. "<<total<<endl;
		cout<<" Masukkan jumlah uang anda : Rp.";
		cin>>uang;
		back =  uang - total;
		cout<<" uang kemablian anda : Rp. "<<back<<endl;
		
	}
	else{
		jurusan = "anoynmous";
	}
	
	cout<<"================================"<<endl;
	
	cout<<"apakah anda ingin pembayar lagi (Y : T) : ";
	cin>>ulang;
	}while(ulang== "Y" || "y");
	
	
	cout<<"terima kasih :) ";
	
}
