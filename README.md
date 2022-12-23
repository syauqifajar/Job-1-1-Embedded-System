# Job-1-1-Embedded-System
Jobsheet 1-1 Embedded System : JARINGAN SENSOR NIRKABEL MENGGUNAKAN ESP-NOW

# Jobsheet-1-1-Embedded-System
Jobsheet 1-1 : JARINGAN SENSOR NIRKABEL MENGGUNAKAN ESP-NOW


A. Memperoleh MAC Address ESP32 Receiver

1. Buka Arduino IDE

2. Kemudian ketikkan script program berikut di Arduino IDE.

![image](https://user-images.githubusercontent.com/121012286/209136564-1aef01df-238b-4dd3-a5b7-4e7f78674492.png)

3. Upload program tersebut ke ESP32.

4. Setelah program berhasil diupload, buka serial monitor.

5. Catat Mac Address ESP32.

![WhatsApp Image 2022-12-22 at 19 46 14](https://user-images.githubusercontent.com/121012286/209137456-c8fbe224-0493-4daf-ae64-ded464bfc93a.jpeg)


B. ESP-NOW One-Way Point-to-Point Communication


Setelah ESP32 sender dikonfigurasi, kemudian konfigurasikan ESP32 yang lain sebagai Receiver. Ketikkan script program berikut untuk mengkonfigurasi ESP32 sebagai receiver.

sender
![image](https://user-images.githubusercontent.com/121012286/209260789-1914f04b-8ef9-4bbf-8994-2add1807e97f.png)

receiver
.

Aturlah jarak awal komunikasi antara sender dan receiver yaitu 1 meter. Kemudian ubah jarak komunikasi dengan penambahan 1 meter. Data yang dikirim pada tiap iterasi pengujian adalah 10 data. Aturlah tinggi antena atau peletakan ESP32 pada ground level (menempel tanah), 30 cm di atas tanah, dan 1 meter di atas tanah.

<img width="325" alt="image" src="https://user-images.githubusercontent.com/121012286/209325103-ec4bd959-f2f8-48e9-9310-42a4175fceb5.png">

TX-RX Ground 1 meter 

TX

<img width="217" alt="TX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209326180-33851eb4-9dd9-4311-9e4c-523c852bde0d.png">

RX

<img width="608" alt="RX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209326231-a4c7bd9d-f37c-47d1-9954-76c934a59310.png">

Ground 2 meter

TX

<img width="524" alt="TX ground 2 meter" src="https://user-images.githubusercontent.com/121012286/209327053-44d25ede-d9ff-4b0b-9cf4-9c2629cac57b.png">

RX

<img width="605" alt="RX ground 2 meter" src="https://user-images.githubusercontent.com/121012286/209327088-dd17db10-49e4-4e6a-acfb-d98940bc2185.png">

Ground 3 meter

TX

<img width="539" alt="TX Ground 3 meter" src="https://user-images.githubusercontent.com/121012286/209327133-5bc74a9f-45cf-46d3-bc8d-3893ba222f96.png">

RX

<img width="611" alt="RX ground 3 meter" src="https://user-images.githubusercontent.com/121012286/209327158-624793d4-1e10-4380-9496-24dfc8ef8526.png">

Ground 4 meter

TX

<img width="536" alt="TX ground 4 mtr" src="https://user-images.githubusercontent.com/121012286/209327209-be51e7cc-3989-4179-81e1-103700e25cd9.png">

RX

<img width="608" alt="RX ground 4 meter" src="https://user-images.githubusercontent.com/121012286/209327388-4af86198-df09-45a3-a940-284426c9cd06.png">

Ground 5 meter

TX

<img width="609" alt="RX 5 meter" src="https://user-images.githubusercontent.com/121012286/209327425-0179254a-98d1-43dc-bbd2-0c3c42f2e58c.png">

RX

<img width="609" alt="RX 5 meter" src="https://user-images.githubusercontent.com/121012286/209327489-7b60704c-9db3-46b4-8d60-78ea34fc3a59.png">

TX-RX 30 cm 1 meter

TX

<img width="217" alt="TX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209327782-f608c43b-1332-46a9-85ec-d1af641d995f.png">

RX

<img width="605" alt="RX ground 2 meter" src="https://user-images.githubusercontent.com/121012286/209327861-321aa7f7-3198-4132-90e6-eb53a4d5eabd.png">

30 cm 2 meter

TX

<img width="217" alt="TX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209327907-984f3c0c-493b-49a2-9658-7f3292a83840.png">

RX

<img width="608" alt="RX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209327964-7ff8e698-a1cc-4cd0-8f7a-3acecdaa15b6.png">

30 cm 3 meter

TX

<img width="217" alt="TX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209328015-21bde002-84f3-469e-ba29-5a49a6a6833a.png">

RX

<img width="608" alt="RX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209328032-5fc54ded-dff9-46d4-a22a-1479f806ebf4.png">

30 cm 4 meter

TX

RX
<img width="608" alt="RX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209328215-246def29-959e-46cc-9d71-f9eeaf206b01.png">

30 cm 5 meter

TX
<img width="524" alt="TX ground 2 meter" src="https://user-images.githubusercontent.com/121012286/209328272-d28515ff-b101-4ea0-92cf-8b2b1e571649.png">

RX
<img width="608" alt="RX ground 4 meter" src="https://user-images.githubusercontent.com/121012286/209328555-020c216d-6642-4e84-a361-68e9a49e602d.png">

TX-RX 1 meter 1 meter

TX

<img width="536" alt="TX ground 4 mtr" src="https://user-images.githubusercontent.com/121012286/209328691-4c1cb0df-635a-458a-8631-6a486a652217.png">

RX
<img width="608" alt="RX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209328717-5918d4aa-e206-4333-bddc-b6d2dd9f8a65.png">

1 meter 2 meter

TX

<img width="524" alt="TX ground 2 meter" src="https://user-images.githubusercontent.com/121012286/209328786-d483d437-c7e9-4bef-890b-66f2e262256e.png">

RX
<img width="608" alt="RX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209328884-d5200b6c-ac83-4735-94f8-6c0873505d14.png">

1 meter 3 meter

TX
<img width="536" alt="TX ground 4 mtr" src="https://user-images.githubusercontent.com/121012286/209328944-4f11fc60-d727-46a1-813c-b1f84872ee59.png">

RX
<img width="608" alt="RX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209328960-4455a680-3b85-4de9-b14a-2397ccb6ca59.png">

1 meter 4 meter

TX
<img width="524" alt="TX ground 2 meter" src="https://user-images.githubusercontent.com/121012286/209329055-000e8ac7-4de1-43d9-bd42-eb128d53b3fc.png">

RX
<img width="608" alt="RX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209329073-0b4482dd-3d02-47a5-94de-add170de27a2.png">

1 meter 5 meter

TX
<img width="536" alt="TX ground 4 mtr" src="https://user-images.githubusercontent.com/121012286/209329113-053c5288-cd60-46bd-9d04-f47030f3c0cd.png">

RX
<img width="608" alt="RX ground 1 meter" src="https://user-images.githubusercontent.com/121012286/209329132-8cc75109-2bb1-4109-9feb-7b81a1c5dfcb.png">

C. One-Way, One-to-Many Communication

a) Mengirim Pesan yang Sama Ke Beberapa Board ESP32

MAC Sender (Syauqi & Vania) : 3C:71:BF:F1:4B:08 
MAC Reciver 1 (Noviantie & Dionysius) : 24:6F:28:02:C3:1C 
MAC Receiver 2 (Hesti & Nabila) : 24:0A:C4:C6:06:54
MAC Receiver 3 (Cantika & Razan) : 30:AE:A4:7A:8F:B8

Sender (Syauqi & Vania)
<img width="394" alt="langkah C" src="https://user-images.githubusercontent.com/121012286/209329722-e0db1e3b-2bd5-4c61-88da-3fa6d7f66c89.png">


Reciver 1 (Noviantie & Dionysius)

<img width="605" alt="langkah C mamah" src="https://user-images.githubusercontent.com/121012286/209329780-779c688d-54f3-4ac6-8429-0f1d1e7ffbfc.png">


Receiver 2 (Hesti & Nabila)
<img width="610" alt="C bila" src="https://user-images.githubusercontent.com/121012286/209329868-9668e48d-9d6a-4e3d-b0a5-90ec87d5cb6e.png">

Receiver 3 (Cantika & Razan)

<img width="430" alt="C abi" src="https://user-images.githubusercontent.com/121012286/209334764-212c8d3f-7b77-4dfb-a530-55b2dc2d750f.png">

Matikan salah satu board Receiver, dokumentasikasikan hasilnya, dan buatlah analisisnya.

Sender (Syauqi & Vania)

<img width="359" alt="LAngkah C gagal" src="https://user-images.githubusercontent.com/121012286/209334811-6e2f613b-ffa8-469a-b81f-6c84b0858747.png">


Reciver 1 (Noviantie & Dionysius)

<img width="605" alt="langkah C mamah" src="https://user-images.githubusercontent.com/121012286/209334901-f53b8633-754c-43f9-b7e7-2691978edff8.png">


Receiver 2 (Hesti & Nabila)
<img width="608" alt="C bila 2" src="https://user-images.githubusercontent.com/121012286/209334947-3a304be8-4cc2-4e3f-9953-016fea51a923.png">

Receiver 3 (Cantika & Razan)

<img width="485" alt="c abi 2" src="https://user-images.githubusercontent.com/121012286/209335007-badcd825-bcce-4ffc-baa1-3fdbe2c0d9f2.png">

b) Mengirim Pesan yang Berbeda Ke Beberapa Board ESP32

D. One-Way, Many-to-One Communication
MAC Sender 1 (Syauqi & Vania) : 24:0A:C4:C5:E2:DC
MAC Sender 2 (Hesti & Nabila) : 24:6F:28:02:C3:1C 
MAC Sender 3 (Cantika & Razan) : 24:0A:C4:C6:0E:7C 
MAC Receiver (Dionysius & Noviantie) : 3C:71:BF:F1:42:70

Sender
<img width="362" alt="D1" src="https://user-images.githubusercontent.com/121012286/209335423-0642e4dd-6ab7-4edc-bb2b-88eb850306c7.png">

Receiver

<img width="608" alt="D receive" src="https://user-images.githubusercontent.com/121012286/209335493-a32f6287-4a09-47f6-8c4d-7cc8c6449a65.png">

E. Two-Way Communication Pengecekan Sensor menggunakan DHT22


<img width="374" alt="D2" src="https://user-images.githubusercontent.com/121012286/209335535-16a0debb-ac41-4373-9227-fda5688f10b3.png">


