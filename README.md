Full Source : https://developer.mozilla.org/en-US/docs/Web/HTTP/Status

#Information responses
###100 – Continue
Maksudnya adalah server sudah menerima permintaan dari browser dan sekarang sudah siap untuk menerima permintaan.

###101 – Switching Protocols
Browser meminta server untuk mengganti/berpindah protokol dan server telah memenuhi permintaan tersebut.

###103 – Early Hints
HTTP code yang satu ini berarti server mengirimkan "header" terlebih dahulu ke browser sebelum data dari server sepenuhnya terbuka

#Successful responses
###200 - Everything is OK
Kode ini muncul saat halaman website atau data bekerja sebagaimana mestinya.

###201 – Created
Server telah memenuhi permintaan browser. Hasilnya, server membuat data baru.

###202 - Accepted
Server sudah menerima permintaan browser, tapi masih diproses.

###203 – Non-Authoritative Information
HTTP code yang satu ini muncul saat penggunaan proxy berhasil dideteksi.

###204 – No Content
Maksudnya adalah server sudah berhasil memproses permintaan, tapi tidak menghasilkan konten apapun.

###205 – Reset Content
Hampir mirip dengan kode 204. HTTP code 205 ini berarti server telah memproses permintaan, tapi tidak menghasilkan konten apapun. 

###206 – Partial Content
Kode ini muncul saat browser menggunakan “range header.” Sehingga menyebabkan server hanya mengirim sebagian dari data yang diminta.

#Redirection messages
###300 – Multiple Choices

###301 – The requested resource has been moved permanently
Kode ini muncul saat halaman website atau data telah diganti secara permanen dengan data yang baru

###302 – The requested resource has moved, but was found
HTTP code yang satu ini terjadi saat data yang diminta itu ditemukan, tapi tidak berada di lokasi yang dikira. 

###303 – See Other

###304 – The requested resource has not been modified since the last time you accessed it
Kode ini memberitahu browser bahwa data yang disimpan di cache itu tidak berubah. Sehingga halaman website bisa lebih cepat dibuka.

###307 – Temporary Redirect
Muncul saat data telah dipindah sementara di URL yang berbeda. Namun, metode HTTP masihlah sama.

###308 – Permanent Redirect
Berarti data yang diminta telah dipindah secara permanen di URL baru. Namun, metode HTTP juga masih sama.

##Client error responses

###400 – Bad Request
Server tak bisa memenuhi permintaan karena adanya error dari browser.

###401 – Unauthorized
Error ini muncul karena browser tak bisa memberikan bukti kewenangan yang sah saat diminta server.

###402 – Payment Required

###403 – Access to that resource is forbidden
Kode ini muncul saat pengguna berusaha mengakses sesuatu yang tak diizinkan.

###404 – The requested resource was not found
Halaman tidak ditemukan

###405 – Method not allowed
Kode ini menunjukkan bahwa server hosting telah menerima dan mengenali permintaan dari browser.

##Server error responses
###502 – Bad Gateway
HTTP status code ini muncul karena salah satu server menerima respons yang tak beres dari server lainnya. 
