mkprefix - Membuat address list mikrotik dari prefix BGP
--------------------------------------------------------

Ini adalah skrip untuk membuat address-list mikrotik dari router bgp
dengan bantuan ssh. Cara kerjanya adalah script ini akan melakukan query bgp
kemudian diparsing.

Contoh
======

Router bgp mempunyai ip 192.168.1.1, port ssh adalah 2222. Berkas konfigurasi
adalah example.conf dan example.cmd. Berkas example.con mempunyai informasi
tentang ip router target, user untuk login dan port ssh. Sedangkan example.cmds
adalah perintah yang akan dilakukan *setelah* skrip melakukan ssh untuk
mendapatkan prefix. Pada example.cmd perintah yang dilakukan untuk mendapatkan
prefix adalah perintah bgp vyatta.

Untuk mengeksekusi silakan ketik::
	./mkprefix example



Mahyuddin Susanto
<udienz@rad.net.id>
