# Teknik Elektro Server Config

Dokumentasi & backup konfigurasi server infrastruktur Jurusan Teknik Elektro POLNAM.

## Stack
- Ubuntu 22.04 (VirtualBox)
- Apache2 (reverse-proxied via Cloudflared Tunnel)
- MariaDB
- PHP 8.3
- Nextcloud + OnlyOffice (Docker)
- Webmin (administrasi server)

## Virtual Hosts

| Server Name | Document Root |
|---|---|
| cloud.teknikelektro.net | /var/www/cloud |
| arsip.teknikelektro.net | /var/www/html/e-archive/public |
| kotakasaran.teknikelektro.net | /var/www/kotaksaran |
| laboratorium.teknikelektro.net | /var/www/html/laboratory_management |
| magang.teknikelektro.net | /var/www/html/magang2 |
| repository.teknikelektro.net | /var/www/html/repository_jte |
| monitoringlab.teknikelektro.net | /var/www/monitoring_lab/public |

File konfigurasi lengkap tiap host ada di folder `apache/`.
