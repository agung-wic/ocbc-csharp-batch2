Kode Peserta : FSDO012ONL012
Nama Peserta : Agung Wicaksono

Tata Cara Penggunaan:

1. Jalankan ASP.NET Core Web API pada folder Kantor_WebAPI
2. Gunakan Postman untuk melihat hasil
3. Berikut Endpoint untuk mengakses API
	a. https://localhost:44356/api/employee ->untuk menampilkan seluruh data gunakan GET
	b. https://localhost:44356/api/employee ->untuk memasukan data baru gunakan POST 
	   dan isi data yang ingin dimasukan pada bagian body dengan format JSON
	c. https://localhost:44356/api/employee/{id} ->untuk mengubah data yang sudah ada
	   gunakan PUT dan isi data yang ingin diubah pada bagian body
	d. https://localhost:44356/api/employee/{id} -> untuk menghapus data gunakan DELETE
	e. https://localhost:44356/api/employee/{id} -> untuk mencari data berdasarkan id gunakan GET