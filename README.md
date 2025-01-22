# pln-token

sebelas digit angka di bagian atas atau bawah barcode kotak meteran listrik yang terpasang di rumah. Untuk melakukan pengisian pulsa listrik, kamu perlu memasukkan nomor meteran yang sesua

example nomer pelanggang 321203131053

Result 
````
    "info": {
      "Meter_ID": "14312593289",
      "Pelanggan_ID": "321203131053",
      "Flag": "1",
      "Nama_Pelanggan": "NAJMAWATI N              ",
      "Tarif": "R1  ",
      "Daya": "000001300"
    }
````


Result pln 
````
   "result_pln": {
      "bit18": "6012",
      "mti": "0210",
      "bit7": "0122061753",
      "bit49": "360",
      "bit39": "00",
      "bit15": "0122",
      "bit37": "000000061753",
      "bit48": "JTL53L314312593289321203131053155A1299693314ED7A2C2C5FF2301C37B2OPT120Z0C5FF3F9591F9066FB90ED48NAJMAWATI N              R1  000001300",
      "bit3": "380000",
      "bit4": "000000000000",
      "bit2": "053502",
      "bit12": "061753",
      "bit13": "0122",
      "bit32": "008",
      "bit11": "061753",
      "bit41": "54JMTO01",
      "bit42": "200900100800000",
      "bit62": "3232121               0000000000000000000000000000"
    }
````

7 digit number 3232121 = geolocation


