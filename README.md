# radit.gitbuh.io
#include <iostream>

    void tampilkanBeranda() {
        std::cout << "SELAMAT DATANG DI\n";
        std::cout << "WEBSITE KELOMPOK 4 KELAS A KEPERAWATAN\n";
        std::cout << "Kami di sini dengan satu tujuan utama: memberikan Anda informasi terkini dan komprehensif mengenai Diabetes Mellitus.\n";
        std::cout << "Dalam website ini, Anda akan menemukan berbagai artikel, panduan, dan sumber daya lainnya yang dirancang untuk membantu Anda\n";
        std::cout << "memahami, mencegah, dan mengelola kondisi ini dengan lebih baik. Kami berharap Anda mendapatkan manfaat maksimal dari\n";
        std::cout << "konten yang kami sajikan. Selamat menjelajah dan jangan ragu untuk menghubungi kami jika Anda memiliki pertanyaan lebih lanjut!\n";
    }
    
    void tampilkanTentangKami() {
        std::cout << "ASKEP DIABETES MELITUS\n";
        std::cout << "Disponsori : Kelompok 4 Kelas A Keperawatan\n";
    }
    
    void tampilkanMateri() {
        std::cout << "DIABETES MELLITUS\n";
        std::cout << "1. PENGERTIAN DAN DEFINISI\n";
        std::cout << "2. JENIS-JENIS DIABETES MELLITUS\n";
        std::cout << "3. PENYEBAB DAN FAKTOR RISIKO\n";
        std::cout << "4. DIAGNOSIS DIABETES MELLITUS\n";
        std::cout << "5. PENGELOLAAN DAN PENGOBATAN\n";
        std::cout << "6. PENCEGAHAN DIABETES MELLITUS\n";
    }
    
    void tampilkanAnggota() {
        std::cout << "ANGGOTA KELOMPOK 4\n";
        std::cout << "1. Nurnisa Salsabila Lasimpala - KELAS A KEPERAWATAN\n";
    }
    
    void tampilkanKontakKami() {
        std::cout << "Hubungi Kami\n";
        std::cout << "+6282291601249\n";
        std::cout << "Email Kami\n";
        std::cout << "muhammadgustisioni@gmail.com\n";
    }
    
    int main() {
        std::cout << "KELOMPOK 4\n";
        std::cout << "1. Beranda\n";
        std::cout << "2. Tentang Kami\n";
        std::cout << "3. Materi\n";
        std::cout << "4. Anggota\n";
        std::cout << "5. Kontak Kami\n";
        std::cout << "Pilih menu: ";
        
        int pilihan;
        std::cin >> pilihan;
    
        switch (pilihan) {
            case 1:
                tampilkanBeranda();
                break;
            case 2:
                tampilkanTentangKami();
                break;
            case 3:
                tampilkanMateri();
                break;
            case 4:
                tampilkanAnggota();
                break;
            case 5:
                tampilkanKontakKami();
                break;
            default:
                std::cout << "Pilihan tidak valid.\n";
        }
    
        std::cout << "© KELOMPOK 4\n";
        return 0;
    } 
