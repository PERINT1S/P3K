---
layout: default
title: Keamanan Digital
parent: teknologi
nav_order: 3
---

Panduan ini sengaja disusun sebagai _check list_ untuk membantu kita terbiasa menjaga kebersihan dan keamanan perangkat digital kita. Ada banyak panduan yang lebih komprehensif dan bisa kamu cek di [pranala luar](#pranala-luar). Jangan khawatir jika tidak semuanya dapat kamu lakukan. Sama seperti kita mulai menjaga kebersihan, atau belajar mengurangi sampah, membangun kebiasaan dilakukan dengan bertahap. Semakin sering dilakukan, semakin sering kita terbiasa.

Last updated: 23 Mei 2020

## Daftar isi
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Amankan akun & gunakan ~~kata~~ frasa sandi

- [ ] HAPUS semua penggunaan no. HP-mu sebagai _recovery phone_ dan 2FA melalui SMS atau telpon. Jika menggunakan 2FA, gunakan aplikasi seperti [FreeOTP](https://freeotp.github.io/) atau Google Authenticator.
- [ ] Jangan gunakan password yang sama untuk lebih dari satu akun
- [ ] Gunakan password kuat: panjang (15 karakter++),  huruf besar/kecil, angka, simbol, spasi.
- [ ] Gunakan **password manager** seperti KeePassXC.
  - [ ] Gunakan master password yang kuat tapi dapat kamu ingat. Awas jangan kelupaan master password atau password masuk komputer/perangkat...
  - [ ] Ingat kalau orang tahu master passwordmu, dia bisa akses banyak akunmu
  - [ ] Password2 komputer/device baiknya dihafal
  - [ ] Coba biasakan dgn akun-akun low-risk dulu (misal: subscription newsletter, dsb)
- [ ] Sebisa mungkin, **jangan masukkan data tanggal lahir asli** dalam akunmu. Masukkan info tanggal lahir buatan tersebut ke dalam Password Manager.
- [ ] Waspada terhadap _phishing_ spam dan virus – jangan sembarang mengklik tautan (link) yang dikirimkan orang, sekalipun kamu kenal. **Jika kamu ragu atau merasa aneh: jangan buka**.
- [ ] Cek apakah akunmu pernah terlibat dalam kebocoran data (_data breach_) di [monitor.firefox.com](https://monitor.firefox.com) atau [haveibeenpwnd.com](https://haveibeenpwnd.com). Jika ya, ganti sandi akun tersebut, dan akun-akun yang menggunakan sandi yang serupa.
- [ ] Baiknya, **pisah-pisahkan email untuk berbagai urusan**. Misal: email untuk personal, kerja, advokasi yang berbeda-beda, bank, ojol, medsos, dsb. Pisahkan Gmail Androidmu dengan Gmail yang biasa kamu gunakan. Ini untuk menghindari satu email compromised, merambat ke akun-akun lain. Susah ingat? Gunakan password manager.
- [ ] **Gunakan VPN**. Beberapa rekomendasi a.l. [ProtonVPN](https://protonvpn.com/), [RiseUpVPN](https://riseup.net/en/vpn).
- [ ] Rajin review keamanan & privasi Google-mu di https://myaccount.google.com. Secara berkala bersihkan Google-mu dari data sensitif/lama. Gunakan akun Google terpisah yang tidak diketahui orang untuk data sensitif yang masih memerlukan layanan Google.
- [ ] Mencari **alternatif email** selain Gmail dan Yahoo? Rekomendasi kami: Protonmail, yang juga menyediakan ProtonVPN. Atau TutaNota.

# Handphone/tablet

- [ ] Pasang password yang kuat, bukan tanggal lahir sendiri/pasangan/anggota KK, dsb.
- [ ] Enkripsi HP dan storage.
- [ ] Samarkan nama HPmu agar identitasmu tidak terpapar (mis: Budi's iPhone → Maruko)
- [ ] Update OS dan aplikasi -- nyalakan notifikasi untuk memberitahu jika ada update
- [ ] Secara berkala, periksa izin aplikasi, lihat aplikasi apa saja yang dapat mengakses lokasimu, galeri, kamera, mikrofon, kontak, kalender, dsb.
- [ ] Pasang anti-virus: Beberapa rekomendasi: Kaspersky, MalwareBytes (Android); Avira (iOS).
- [ ] Gunakan secure browser dengan tingkat keamanan & privasi yang baik, atau pisahkan untuk berbagai kepentingan. Beberapa rekomendasi: Tor atau Onion Browser, Firefox, Brave. Gunakan Private Window untuk mengurangi rekaman riwayat peramban dan penyimpanan cookies.
- [ ] Gunakan aplikasi chat yang terenkripsi dan nyalakan timer untuk otomatis menghapus pembicaraan sensitif. Beberapa rekomendasi: Signal, Session, Deltachat, Keybase, Wire.
- [ ] Secara berkala cek dan hapus/tinggalkan grup yg tidak lagi perlu/aktif. Ingat, banyak grup dan/atau tidak menghapus pesan sensitif = panen data & kontak saat HPmu tersita.
- [ ] Rajin backup, dan pastikan terenkripsi
- [ ] Secara berkala, pindahkan atau hapus data, khususnya yang sensitif dari ponsel. Jika masih diperlukan, simpan di luar ponsel di tempat yang aman dan terenkripsi
- [ ] Hapus aplikasi-aplikasi yang tidak kamu perlukan
- [ ] Untuk pengguna Android, ada aplikasi seperti Tella untuk dokumentasi sensitif yang dapat disamarkan atau dihapus seketika.
- [ ] Bisa juga aktifkan Find My Device ([Android](https://www.google.com/android/find) & [Apple iCloud](https://www.apple.com/icloud/find-my/
)) dan _remote device wipe_ (menghapus atau lacak HPmu jika hilang/dicuri/disita). Namun sadari juga resikonya: (1) jika seseorang berhasil mendapat akses ke Google/Apple IDmu, jadi pastikan akun tersebut aman! (2) Jika HPmu disita aparat sebagai barang bukti, _remote device wipe_ mungkin tidak dapat sembarang dilakukan (malah membuat curiga ketika perangkatmu kosong). Selengkapnya:
* Android https://support.google.com/accounts/answer/6160491   
* iPhone: https://support.apple.com/id-id/HT205362  

# Desktop/laptop

- [ ] Pasang password yang kuat
- [ ] Enkripsi dengan BitLocker untuk Windows 10, FileVault untuk Mac. Jika tidak ada, encrypt data sensitif dengan VeraCrypt atau Cryptomator.
- [ ] Samarkan nama komputermu agar identitasmu tidak terpapar (Budi’s Lenovo → iwakku)
- [ ] Matikan komputer jika tidak digunakan. Ingat enkripsi tidak aktif jika komputer menyala.
- [ ] Nyalakan firewall
- [ ] Update OS dan software.
- [ ] Jika menggunakan Firefox atau Chrome, install NoScript, Ublock Origin, Privacy Badger, HTTPS only.
- [ ] Gunakan browser berbeda untuk kepentingan berbeda (e.g. Google-related work di Chrome, kerja sensitif di Tor, browsing di Brave, dsb.).
- [ ] Hapus history & cookies secara berkala.
- [ ] Pasang Anti-Virus (misal: Malware Bytes), atau jika menggunakan Windows 10, aktifkan Windows Defender.
- [ ] Jangan sembarang memasang flashdisk tak dikenal ke komputer. Scan dulu.
- [ ] Backup secara berkala dan dengan enkripsi

# Bacaan lanjutan

**[Digital Hygiene 101](https://coconet.social/digital-hygiene-safety-security/)**  
Tips kebersihan digital dari COCONET, juga tersedia dalam [bahasa Indonesia](https://coconet.social/digital-hygiene-safety-security-indonesia)

**[Digital First Aid Kit](https://digitalfirstaid.org/en/index.html)**, panduan jika kamu mengalami gawai hilang atau berperilaku mencurigakan (apakah disadap?), situs web tidak berjalan, kehilangan akses akun, dsb.

**[Digital Safety Manual](https://digitalsafetymanual.org/)** yang dikembangkan oleh [Digital Defenders](https://digitaldefenders.org/).

**[Security in a Box](https://securityinabox.org/en/)**, peralatan dan taktik untuk keamanan digital, juga tersedia dalam [bahasa Indonesia](https://securityinabox.org/id/).
