# Panduan Mengaktifkan Windows 11 Pro Secara Gratis

Upgrade ke Windows 11 Pro memberikan fitur tambahan seperti enkripsi BitLocker dan kemampuan untuk menghosting perangkat Anda sebagai Desktop Eksternal yang dapat diakses melalui internet. Anda juga bisa beralih dari hampir semua edisi Windows ke Pro secara gratis.

Jika Anda sudah memiliki Windows 11 Pro tetapi belum diaktivasi, Anda bisa langsung menuju bagian **Mengaktifkan Windows Pro**.

## Langkah-langkah Aktivasi

Untuk mengaktifkan Windows 11 Pro, ikuti langkah-langkah berikut:

**1. Buka Command Prompt sebagai Administrator**

- Tekan `Windows-logo key + R` untuk membuka dialog Run.
- Ketik `cmd.exe` dan tekan Enter.
- Di jendela Command Prompt, tekan `Ctrl + Shift + Enter` untuk membukanya dengan hak administratif.
- Klik "Yes" saat diminta oleh User Account Control.

**2. Hapus Kunci Produk dan Konfigurasi KMS**

- Hapus Kunci Produk Saat Ini:
  ```shell
  slmgr.vbs /upk
