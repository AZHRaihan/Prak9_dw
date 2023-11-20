# Prak9_dw
Tugas
1. Buatkan kodenya di kode editor favorit kalian
2. Jalankan di web browser favorit
3. Buka inspect element dan lihat consolenya
4. Jelaskan secara terstruktur maksud dari HTML, CSS, dan JavaScriptnya.
5. Lampirkan printscreen halaman web kalian.

HTML

•	div id="slider">...</div>: Ini adalah container untuk slider gambar. Setiap gambar di dalam slider ditempatkan di sini.

•	img src="..." alt="...">: Ini adalah tag untuk menampilkan gambar dalam HTML. Setiap gambar memiliki atribut src yang berisi URL gambar dan atribut alt yang berisi teks alternatif untuk aksesibilitas.

•	div id="slider-controls">...</div>: Ini adalah container untuk kontrol slider. Kontrol ini berupa bullet points atau elemen yang digunakan untuk mengganti gambar pada slider.

•	span class="slider-control" data-index="0">1</span>: Ini adalah salah satu kontrol slider. Setiap span ini mewakili satu gambar pada slider. Atribut data-index digunakan untuk menunjukkan indeks gambar yang terkait.

•	script src="./script.js"></script>: Ini adalah tag untuk menyertakan file JavaScript. File script.js berisi kode JavaScript yang mengendalikan perilaku slider.


CSS
1.	#slider

•	margin: Menetapkan margin di atas dan bawah dan secara otomatis menentukan margin kiri dan kanan agar slider berada di tengah.

•	position: Mengatur posisi elemen.

•	width dan height: Menetapkan dimensi slider.

•	overflow: Mengatasi gambar yang mungkin melebihi ukuran slider.

•	border: Menetapkan border dengan warna #ddd untuk tampilan yang lebih jelas.

•	border-radius: Memberikan sudut border yang lebih lembut.

•	box-shadow: Menambahkan efek bayangan untuk memberikan kedalaman.

3.	#slide img
	
•	position: Memposisikan gambar secara absolut di dalam slider.

•	width dan height: Menetapkan dimensi gambar sebagai 100% lebar dan tinggi slider.

•	display: Menyembunyikan gambar secara default.

•	transition: Menambahkan efek transisi untuk perubahan opacity.

•	img.active: Menampilkan gambar yang memiliki kelas 'active' dengan opacity 1.

5.	#slider-controls

•	text-align: Pusatkan teks pada elemen kontrol.

•	margin-top: Memberikan jarak antara slider dan kontrol.

7.	#slider-controls .slider-control

•	cursor: Mengubah kursor saat diarahkan ke kontrol.

•	padding dan margin-right: Menetapkan ruang di sekitar teks dan memberikan jarak antara kontrol.

•	user-select: Mencegah teks terpilih saat mengklik kontrol.

•	background-color dan color: Menetapkan warna latar belakang dan teks kontrol.

•	border dan border-radius: Menetapkan border dan memberikan sudut yang lebih lembut pada kontrol.

•	transition: Menambahkan efek transisi untuk perubahan warna latar belakang saat hover.

•	:hover: Mengatur tampilan saat kontrol dihover.

•	.active: Mengatur tampilan kontrol saat aktif.

JavaScript

•	Saat halaman dimuat, event listener untuk 'DOMContentLoaded' diaktifkan.

•	Variabel current digunakan untuk melacak indeks gambar yang sedang ditampilkan.

•	NodeList images dan controls menyimpan elemen-elemen gambar dan kontrol dari DOM.

•	Fungsi showImage(index) mengubah tampilan gambar dan status kontrol sesuai indeks yang diberikan.

•	Fungsi startAutoSlide dan stopAutoSlide digunakan untuk mengatur otomatisasi slider.

•	Event listener ditambahkan pada setiap elemen kontrol untuk merespons klik dan mengubah tampilan sesuai indeks.

•	Slider otomatis dimulai saat halaman dimuat.

