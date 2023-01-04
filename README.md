#include <iostream>
using namespace std;
string tujuan,kelas;
float harga, diskon, totaldiskon, totalharga;
float penentuandiskon(string kelas, int umur){
    if (kelas=="BISNIS"){
        if (umur>=50){
            cout<< "Dapat Potongan 1%";
            diskon = 0.01;
        }else if (umur <= 3){
            cout<< "Dapat Potongan 2%";
            diskon = 0.02;
        }
    }
    if (kelas=="FIRST CLASS"){
        if (umur>=45){
            cout<< "Dapat Potongan 0,7%";
            diskon = 0.007;
        }else if (umur <= 3){
            cout<< "Dapat Potongan 0,9%";
            diskon = 0.009;
        }
    }
        return diskon;
}
float vipclass (string kelas,string tujuan){
    if(kelas=="FIRST CLASS"){
        if (tujuan=="UAE"){
            cout << "==================================\n";
            cout << "|     MASKAPAI     |    JADWAL   |"<<endl;
            cout << "==================================\n";
            cout << "| ETIHAD           | 17:05-05:15 |"<<endl;
            cout << "| EMIRATES         | 17:40-23:05 |"<<endl;
            cout << "| TURKISH AIRLINES | 04:30-01:00 |"<<endl;
            cout << "==================================\n";
            harga = 400000;
        }
        else if(tujuan=="JEPANG"){
            cout << "====================================\n";
            cout << "|      MASKAPAI      |   JADWAL    |"<<endl;
            cout << "====================================\n";
            cout << "| ALL NIPPON AIRWAYS | 21:45-14:55 |"<<endl;
            cout << "| THAI AIRWAYS       | 06:20-22:40 |"<<endl;
            cout << "| SINGAPORE AIRLINES | 14:00-03:15 |"<<endl;
            cout << "====================================\n";
            harga = 450000;
        }
        else if(tujuan=="USA"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| AMERICAN AIRLINES | 00:25-23:38(+1H) |"<<endl;
            cout << "| EMIRATES          | 17:40-08:15(+1H) |"<<endl;
            cout << "| QATAR AIRWAYS     | 18:20-14:10(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 500000;
        }
        else if(tujuan=="QATAR"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 400000;
        }
        else if(tujuan=="ARAB"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 400000;
        }
        else if(tujuan=="IRAN"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 400000;
        }
        else if(tujuan=="CHINA"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 400000;
        }
        else if(tujuan=="CROATIA"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 400000;
        }
        else if(tujuan=="FRANCE"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 400000;
        }
        return harga;
    }
}
float businesclass (string kelas,string tujuan){
 if (kelas=="BISNIS"){
        if(tujuan=="UAE"){
            cout << "========================================\n";
            cout << "|        MASKAPAI        |    JADWAL   |"<<endl;
            cout << "========================================\n";
            cout << "| ETIHAD                 | 00:40-18:35 |"<<endl;
            cout << "| SAUDI ARABIAN AIRLINES | 08:35-23:00 |"<<endl;
            cout << "| GARUDA INDONESIA       | 16:30-08:45 |"<<endl;
            cout << "========================================\n";
            harga = 300000;
        }
        else if(tujuan=="JEPANG"){
            cout << "==================================\n";
            cout << "|     MASKAPAI     |    JADWAL   |"<<endl;
            cout << "==================================\n";
            cout << "| EVA AIR          | 14:20-11:55 |"<<endl;
            cout << "| CATHAY PACIF     | 18:30-18:00 |"<<endl;
            cout << "| GARUDA INDONESIA | 23:35-14:10 |"<<endl;
            cout << "==================================\n";
            harga = 350000;
        }
        else if(tujuan=="USA"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 300000;
        }
        else if(tujuan=="QATAR"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
             harga = 300000;
        }
        else if(tujuan=="ARAB"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 350000;
        }
        else if(tujuan=="IRAN"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 300000;
        }
        else if(tujuan=="CHINA"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
             harga = 300000;
        }
        else if(tujuan=="CROATIA"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 350000;
        }
        else if(tujuan=="FRANCE"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 300000;
        }
        return harga;
    }
}
float economiclass(string kelas,string tujuan){
if (kelas=="EKONOMI"){
        if(tujuan=="UAE"){
            cout << "========================================\n";
            cout << "|        MASKAPAI        |    JADWAL   |"<<endl;
            cout << "========================================\n";
            cout << "| ETIHAD                 | 09:35-23:10 |"<<endl;
            cout << "| QATAR AIRWAYS          | 14:00-01:30 |"<<endl;
            cout << "| SAUDI ARABIAN AIRLINES | 19:05-13:35 |"<<endl;
            cout << "========================================\n";
            harga = 200000;
        }
        else if(tujuan=="JEPANG"){
            cout << "=================================\n";
            cout << "|     MASKAPAI    |    JADWAL   |"<<endl;
            cout << "=================================\n";
            cout << "| AIR ASIA        | 08:30-08:30 |"<<endl;
            cout << "| SCOOT           | 11:15-08:30 |"<<endl;
            cout << "| ASIANA AIRLINES | 22:30-15:50 |"<<endl;
            cout << "=================================\n";
            harga = 250000;
        }
        else if(tujuan=="USA"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| AMERICAN AIRLINES | 08:45-17:53(+1H) |"<<endl;
            cout << "| EMIRATES          | 00:15-21:20(+1H) |"<<endl;
            cout << "| LION AIR          | 18:00-20:20(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 230000;

        }
        else if(tujuan=="QATAR"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 220000;
        }
        else if(tujuan=="ARAB"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 200000;
        }
        else if(tujuan=="IRAN"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 200000;
        }
        else if(tujuan=="CHINA"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 250000;
        }
        else if(tujuan=="CROATIA"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 300000;
        }
        else if(tujuan=="FRANCE"){
            cout << "========================================\n";
            cout << "|      MASKAPAI     |      JADWAL      |"<<endl;
            cout << "========================================\n";
            cout << "| QANTAS            | 14:30-19:30(+1H) |"<<endl;
            cout << "| BRITISH AIRWAYS   | 20:40-09:09(+1H) |"<<endl;
            cout << "| AMERICAN AIRLINES | 08:45-16:59(+1H) |"<<endl;
            cout << "========================================\n";
            harga = 300000;
        }
        return harga;
    }
}
int main()
{
    int umur,total,tiket;
    string hari,tanggal,ulangi;
    long long nik;
    string maskapai,nama,asal,spasi,kode[5],unik,pembayaran;
    char data;
    cout << "\t==============================";
    cout << "\n== SISTEM PEMBELIAN TIKET PESAWAT INTERNASIONAL ==\n";
    cout << "\t==============================\n\n";
    cout << "TIKET YANG DIPESAN    : ";
    cin >> tiket;
    for(int data=1; data<=tiket; data++){
        getline (cin, spasi);
        cout << "MASUKKAN NAMA ANDA    : ";
        getline (cin, nama);
        cout << "MASUKKAN UMUR ANDA    : ";
        cin >> umur;
        cout << "MASUKKAN NIK KTP ANDA : ";
        cin >> nik;
        getline (cin, spasi);
        cout << "MASUKKAN KOTA ASAL    : ";
        cin >> asal;
        cout << "\n";
        cout << "================\n";
        cout << "|PILIHAN TUJUAN|" << endl;
        cout << "================\n";
        cout << "|     UAE      |" << endl;
        cout << "|     JEPANG   |" << endl;
        cout << "|     USA      |" << endl;
        cout << "|     QATAR    |" << endl;
        cout << "|     ARAB     |" << endl;
        cout << "|     IRAN     |" << endl;
        cout << "|     CHINA    |" << endl;
        cout << "|     CROATIA  |" << endl;
        cout << "|     FRANCE   |" << endl;
        cout << "================\n";
        cout << "\n";
        cout << "PILIH TUJUAN ANDA : ";
        cin>>tujuan;
        if(tujuan!="UAE" && tujuan!="JEPANG" && tujuan!="USA" && tujuan!="QATAR" && tujuan!="CHINA"&& tujuan!="IRAN" && tujuan!="ARAB" && tujuan!="CROATIA" && tujuan!="FRANCE"){
                system("CLS");
                return main();
        }
        cout << "\n";
        cout << "MASUKAN HARI : ";
        cin >> hari;
        cout << "MASUKAN TANGGAL/BULAN/TAHUN : ";
        cin >> tanggal;
        cout << "\n";
        cout << "PILIHAN KELAS : \n";
        cout << "FIRST CLASS\n";
        cout << "BISNIS\n";
        cout << "EKONOMI\n";
        cout << "\n";
        getline(cin,spasi);
        cout << "MASUKAN PILIHAN :";
        getline(cin,kelas);
        cout << "\n";
        harga = vipclass(kelas,tujuan);
        harga = businesclass(kelas,tujuan);
        harga = economiclass(kelas,tujuan);
        diskon = penentuandiskon(kelas, umur);
        totaldiskon = harga*diskon;
        totalharga = harga - totaldiskon;

        cout << "\n";
        cout << "===========================\n";
        cout << "|    KELAS    |   HARGA   |" << endl;
        cout << "===========================\n";
        cout << "| First Class | Rp400.000 |" << endl;
        cout << "| Bisnis      | Rp300.000 |" << endl;
        cout << "| Ekonomi     | Rp200.000 |" << endl;
        cout << "===========================\n";
        cout << "\n\n";
        cout << "MASUKKAN PILIHAN MASKAPAI : ";
        getline(cin,maskapai);
        cout << "\n";
        cout << "METODE PEMBAYARAN" << endl;
        cout << "1. ALFAMART" << endl;
        cout << "2. INDOMART" << endl;
        cout << "\n";
        cout<< "MASUKAN METODE PEMBAYARAN : ";
        cin >> pembayaran;
        cout << "\n";
        kode[0] = "FRST";
        kode[1] = "BSNS";
        kode[2] = "ECO";
        if(kelas=="FIRSTCLASS"){
            unik = kode[0];
        }else if(kelas=="BISNIS"){
            unik = kode[1];
        }else if(kelas=="EKONOMI"){
            unik = kode[2];
        }
        if (pembayaran=="ALFAMART"){
            kode[5] = "ALFT" + unik + "U6RE";
        }else if (pembayaran=="INDOMART"){
            kode[5] = "INDK" + unik + "I8TR";
        }
        cout << "\nApakah Data yang Anda masukkan sudah benar? (y/n) : ";
        cin >> ulangi;
        if(ulangi=="n"){
            system("CLS");
            return main();
        }else if(ulangi=="y"){
            system("CLS");
        }
        cout << endl;
        system ("CLS");
    }
        for(int data=1; data<=tiket; data++){
            cout << "\t=====================\n";
            cout << "\tTiket Pesanan Anda\n";
            cout << "\t=====================\n";
            cout << "1.Nama : " << nama << endl;
            cout << "2.Umur : " << umur << endl;
            cout << "3.Kota Asal : " << asal << endl;
            cout << "4.Tujuan Anda : " << tujuan << endl;
            cout << "5.Kelas Pesawat : " << kelas << endl;
            cout << "6.Nama Maskapai : " << maskapai << endl;
            cout << "7.HARI : " << hari << endl;
            cout << "8.TANGGAL/BULAN/TAHUN : " << tanggal << endl;
            cout << "9.Jumlah Tiket Yang Dipesan : " << tiket << endl;
            cout << "10.Harga Awal : Rp. " << harga << endl;
            cout << "11.Diskon yang didapat : " << diskon*100 << "%" << endl;
            cout << "12.Harga Akhir : Rp." << totalharga << endl;
            cout << "13.KODE PEMBAYARAN : " << kode[5] << endl;
            cout << "\nApakah Anda Ingin Memesan Tiket Lagi ? (y/n) : ";
            cin >> ulangi;
            if(ulangi=="y"){
                system("CLS");
                return main();
            } else {
                return 0;
            }
        }
}
