Recommended to open this ipynb in google colabs and upload Transjakarta.csv file in your google drive (mydrive folder)


Latar Belakang

TransJakarta adalah sebuah sistem transportasi Bus Rapid Transit (BRT) pertama di Asia Tenggara dan Selatan dengan jalur lintasan terpanjang di dunia (208 km). Sistem BRT ini didesain berdasarkan sistem TransMilenio di Bogota, Kolombia. Terhitung sejak 1 Februari 2004, TransJakarta resmi beroperasi Transjakarta merupakan opsi moda transportasi utama masyarakat. Pada bulan April 2023 terdapat jumlah transaksi lebih dari 30000 kali. Transjakarta sangat populer karena memiliki tarif yang terjangkau

Visi: Menghubungkan Kehidupan Jakarta

Misi: Bersama-sama menyediakan layanan transportasi terintegrasi yang memudahkan dan membahagiakan kehidupan Jakarta.

Pada April 2023, Transjakarta menerapkan tarif Rp0 pada banyak koridor. Hal tersebut menyebabkan tidak ada pemasukan yang didapat dari koridor-koridor tersebut. Seluruh biaya operasional dari koridor yang bertarif Rp0 tersebut sepenuhnya bergantung pada dana subsidi dari pemerintah. Selain koridor bertarif Rp0, faktanya koridor yang bertarif Rp3500 dan Rp20000 juga biaya operasionalnya masih disubsidi oleh Pemerintah

Berdasarkan jumlah kendaraan dan jadwal Transjakarta yang saat ini beroperasi, sering ditemui kondisi penumpang yang berdesak-desakan. Hal ini terjadi karena Sarana Transportasi Transjakarta tidak mampu untuk menampung jumlah penumpang yang tiba-tiba membludak pada waktu-waktu tertentu. Kondisi ini tentunya dapat membuat kondisi yang kurang nyaman bagi pengguna TransJakarta

Pengguna Transjakarta mayoritas adalah wanita, bahkan pada beberapa koridor terdapat jumlah wanita yang sangat dominan dibanding dengan jumlah pria pada jam-jam sibuk. Selain wanita, segmen penumpang yang perlu diperhatikan adalah pada sektor Lansia. Meskipun jumlah lansia merupakan jumlah minoritas, tetapi lansia perlu mendapat perlakuan khusus. Oleh karena itu perlu dilakukan peningkatkan fasilitas Transjakarta untuk meningkatkan kenyamananan penumpang Wanita dan Lansia

Rumusan/Batasan Masalah

Bagaimana langkah yang perlu dilakukan untuk menekan biaya operasional dan mengurangi ketergantungan terhadap dana subsidi dari pemerintah
Bagaimana strategi pengelolaan Sistem Transjakarta pada Jam-Jam Padat agar tidak terjadi penumpukan penumpang
Bagaimana langkah awal yang perlu dilakukan untuk mewujudkan Transjakarta yang ramah terhadap wanita dan ramah terhadap lansia


Penjelasan Kolom

- transID: Unique transaction id for every transaction
- payCardID: Customers main identifier. The card customers use as a ticket for entrance and exit.
- payCardBank: Customers card bank issuer name
- payCardName: Customers name that is embedded in the card.
- payCardSex: Customers sex that is embedded in the card
- payCardBirthDate: Customers birth year
- corridorID: Corridor ID / Route ID as key for route grouping.
- corridorName: Corridor Name / Route Name contains Start and Finish for each route.
- direction: 0 for Go, 1 for Back. Direction of the route.
- tapInStops: Tap In (entrance) Stops ID for identifying stops name
- tapInStopsName: Tap In (entrance) Stops Name where customers tap in.
- tapInStopsLat: Latitude of Tap In Stops
- tapInStopsLon: Longitude of Tap In Stops
- stopStartSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
- tapInTime: Time of tap in. Date and time
- tapOutStops: Tap Out (Exit) Stops ID for identifying stops name
- tapOutStopsName: Tap out (exit) Stops Name where customers tap out.
- tapOutStopsLat: Latitude of Tap Out Stops
- tapOutStopsLon: Longitude of Tap Out Stops
- stopEndSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
- tapOutTime: Time of tap out. Date and time
- payAmount: The number of what customers pay. Some are free. Some not.
