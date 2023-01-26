Deteksi Uang Mengguanakan Tensorflow detection
Merujuk dari paper 1527-3516-1-SM.pdf yang berjudul "APLIKASI PENDETEKSI TANDA AIR PADA UANG KERTAS DENGAN METODE SEGMENTASI REGION BASED ACTIVE CONTOUR MENGGUNAKAN MATLAB". dari paper tersebut kami mengembangkan deteksi keaslian uang menggunakan metode tensorflow. project ini bisa dikembangkan menjadi sebuah aplikasi berbasis android agar mendeteksi lebih efesien.
![image](https://user-images.githubusercontent.com/114732960/214845140-0cc0adb8-9576-4124-abe7-4fbf5f074025.png)
![image](https://user-images.githubusercontent.com/114732960/214851024-a559c5e5-5b2e-4a26-a4e7-2946e936993a.png)

1. object-detection.pbtxt atribut untuk mendeteksi objek
2. ssd_mobilenet_v1_pets.config atribut untuk melatih si objek atau membaca ojek
3. uang.pb nama model yang akan di deteksi
4. label_map.pbtxt pemodelan yang akan menjadi output
