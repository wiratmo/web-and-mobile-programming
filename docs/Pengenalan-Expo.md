## Pengenalan Expo

[Expo](https://expo.io/) adalah sebuah *framework* dan *platform* dari React. Expo merupakan sekumpulan *tools* dan *services* yang dibuat menggunakan React Native dan native platform [iOS, Android]. Expo digunakan untuk membangun aplikasi pada iOS, Android, dan web apps dengan menggunakan JavaScript.



### Persiapan penginstalan Expo

1. [Node Js](https://nodejs.org/en/)  merupakan javascript runtime build on  [Chrome's V8 JavaScript engine](https://v8.dev/).

   Rekomendasi menggunakan versi yang [Long Term Support](https://nodejs.org/dist/v14.15.4/node-v14.15.4-x64.msi) (LTS )

2. [Git](https://git-scm.com/downloads) merupakan open source distributed version control system that facilitates GitHub activities on your laptop or desktop .

3. text-editor [[vscode](https://code.visualstudio.com/), [sublime](https://www.sublimetext.com/), [nodepad++](https://notepad-plus-plus.org/downloads/)]

4. Install Expo di Playstore



### Penginstalan Expo

1. Buka Git CMD sehingga muncul tampil seperti Gambar 1.

   <img src="img\git-cmd.PNG" style="zoom:67%;" />

   Gambar 1. Tampilan default Git-CMD.

   

2. *Checking* versi dari nodeJs dan Node package manager (npm adalah package manager for the JavaScript programming language) seperti Gambar 2.

   ```
   node --version
   
   npm --version
   ```

   <img src="img\checking-version.PNG" style="zoom:67%;" />

3. Penginstalan Expo seperti Gambar 3.

   ```
   npm install --global expo-cli
   ```

   <img src="img\npm-expo-cli.PNG" style="zoom:67%;" />

   Gambar 3. Hasil penginstalan expo.

   

4. Membuat projek baru menggunakan expo seperti Gambar 4.

   ```
   expo init projectname
   ```

   - projectname silakan diganti dengan nama project yang akan dibuat

   - selanjutnya diberikan jenis template yang digunakan sebagai default di expo pilih **blank**

   <img src="img\expo-init.PNG" style="zoom:67%;" />

   Gambar 4.  Hasil pembuatan projek expo.

   

5. Membuka project yang tadi dibuat

   ```
   cd projectname
   ```

6. jalankan expo seperti Gambar 5.

   ```
   expo run android
   ```

   <img src="img\hasil-npm-run-android.PNG" style="zoom:67%;" />

   Gambar 5. Hasil expo run android

7. Expo yang terinstall dibuka dan qr code pada langkah ke 6 discan dengan aplikasi tersebut sehingga akan muncul Gambar 6 dan Gambar 7.

   |<img src="img\proses-java-bundle.jpg" style="zoom:30%;" />|<img src="img\expo-berhasil.jpg" style="zoom:30%;" />|
   | --- | ----------- |
   | Gambar 6. Proses building javascript bundle. | Gambar 7. Expo berhasil di install |
