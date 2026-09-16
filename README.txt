CATATAN SHOPIPUT — PWA READY

1. Buka folder ini di VS Code.
2. Pastikan file berada satu folder:
   index.html
   manifest.webmanifest
   sw.js
   icon-192.png
   icon-512.png
3. Klik kanan index.html -> Open with Live Server.
4. Buka alamat localhost/127.0.0.1 dari Live Server di Chrome.
5. Buka F12 -> Application -> Manifest.
6. Pastikan manifest terbaca dan Service Workers menunjukkan sw.js.
7. Jika sebelumnya pernah mencoba versi lama:
   Application -> Service Workers -> Unregister
   Application -> Storage -> Clear site data
   lalu refresh.
8. Di Chrome, gunakan menu browser -> Install app / Install Catatan Shopiput.

Jangan membuka index.html dengan file://.
