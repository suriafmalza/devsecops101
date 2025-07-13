1. Pengurusan Fail & Direktori
Arahan
Fungsi
ls
Senaraikan fail dan folder dalam direktori
cd
Tukar direktori (masuk folder)
pwd
Tunjuk lokasi semasa
mkdir
Cipta direktori/folder baru
rmdir
Padam direktori kosong
rm
Padam fail atau direktori
touch
Cipta fail kosong
cp
Salin fail/direktori
mv
Alih atau tukar nama fail/direktori
cat
Papar kandungan fail
less / more
Papar fail satu halaman demi satu
file
Tunjuk jenis fail
find
Cari fail/direktori


🧑‍💻 2. Pengurusan Pengguna
Arahan
Fungsi
whoami
Papar pengguna semasa
id
Tunjuk UID, GID, dan kumpulan pengguna
adduser / useradd
Tambah pengguna baru
passwd
Tukar kata laluan pengguna
deluser
Padam pengguna
su
Tukar pengguna (switch user)
sudo
Jalankan arahan dengan keizinan root
groups
Papar kumpulan pengguna


🔒 3. Kebenaran Fail (Permissions)
Arahan
Fungsi
chmod
Tukar kebenaran fail/direktori
chown
Tukar pemilik fail/direktori
chgrp
Tukar kumpulan fail


📦 4. Pengurusan Pakej
Arahan
Fungsi
dpkg
Pengurus pakej untuk sistem Debian
apt-get / apt
Pasang, buang, dan kemaskini pakej
yum
Pengurus pakej untuk RHEL/CentOS
rpm
Pasang pakej RPM


🧠 5. Proses & Sumber Sistem
Arahan
Fungsi
ps
Tunjuk proses sedang berjalan
top
Pantau penggunaan CPU & memori masa nyata
kill
Hentikan proses tertentu
uptime
Tunjuk masa aktif sistem
iostat
Statistik I/O CPU dan disk
df
Tunjuk ruang cakera
free
Tunjuk penggunaan RAM
nice
Jalankan proses dengan keutamaan tertentu


🧾 6. Log Sistem
Arahan
Fungsi
journalctl
Papar log sistem (systemd)
tail -f /var/log/syslog
Pantau log masa nyata


🌐 7. Asas Rangkaian & Konfigurasi
Arahan
Fungsi
ifconfig
Papar & konfigurasi interface rangkaian (lama)
ip link
Papar status interface
ip addr
Tunjuk alamat IP
ip route
Tunjuk laluan rangkaian (routing)
ip route add/delete
Tambah atau padam laluan
route -n
Tunjuk jadual routing
dhclient
Minta IP dari DHCP
nmcli
Kawal NetworkManager melalui CLI
arp
Lihat cache ARP
ip neighbour
Papar cache ARP (versi moden)
ping
Uji sambungan ke host lain
traceroute
Jejak laluan paket ke destinasi
netstat
Tunjuk sambungan rangkaian dan port
tcpdump
Analisis paket rangkaian
nslookup
Lakukan carian DNS
dig
Lihat maklumat terperinci DNS
cat /etc/hosts
Lihat pemetaan host ke IP secara lokal


🗃️ 8. Sistem Fail & Kernel
Arahan
Fungsi
mount / umount
Pasang dan nyahpasang sistem fail
df
Semak ruang cakera
du
Tunjuk saiz direktori/fail
lsblk
Papar maklumat peranti storan
dmesg
Papar mesej kernel
















