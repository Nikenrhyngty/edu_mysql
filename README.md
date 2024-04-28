// SQL Syntax JOIN LEFT

SELECT id_mahasiswa, nama_mahasiswa, nama_buku, tgl_pinjam 
from mahasiswa m 
left join peminjaman p 
on id_mahasiswa = id_pinjam
order by nama_mahasiswa 

