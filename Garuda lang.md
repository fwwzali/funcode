# Garuda Programming Language Project

![Linked Train!](https://image.freepik.com/free-vector/garuda-indonesia-illustration-tattoo-tshirt-design_13606-6.jpg)

Tiga orang mahasiswa Teknik Informatika UPNVJT menginisialisasi sebuah open project di Github. **Project** tersebut adalah membuat **bahasa programming baru** yang diberi nama **GARUDA** lang.

Project bahasa baru tersebut sudah dalam tahap penyelesaian penulisan rule sintaksnya. Semua sintaks sudah selesai, tetapi mereka masih belum membuat compiler untuk bahasa **GARUDA** tersebut.

Dengan banyaknya pekerjaan harus mereka kerjakan, mereka membuka kesempatan bagi semua orang (khususnya anak-anak muda Indonesia) untuk menjadi kontributor dalam project mereka. oleh karena itu, dibuat **`branch`** di project mereka.  **`branch`** tersebut diberi nama **`branch compiler`**.

salah satu fungsi dari **`compiler`** adalah mengecek apakah sintaks yang ditulis oleh programmer telah valid atau masih ada kesalahan. dan salah satu proses pengecekan yang dilakukan adalah pengecekan **brackets** `() , <> , {} , []` dari kode yang ditulis oleh programmer.

hal yang harus dipastikan adalah, pasangan bracket yang ada harus sesuai. misalnya:
- `()[]<>` = valid
- `[()]<<>>` = valid
- `{[}]` = tidak valid
- `[[}}<>` = tidak valid
- `{[]<()>}` = valid

silakan anda bergabung menjadi kontributor aplikasi, buatlah aplikasi yang dapat menentukan sebuah code valid atau tidak valid. berikut contoh code sebagai bahan test aplikasi compiler anda:
kode valid:

    Object obj (in inputParams, out outParams)
    {
    	<Blob> myInf = new Blob(function(){
    		       data : [
    				{
	    			               type: image,
    				        size: 100,
    					bg: transparent
    				}
    			      ]
    			})
    			
    	run process_img(){
    		this.myInf.blobToImage({
    			type: jpg
    		})
    	}
    }

  
  kode tidak valid

    Object obj (in inputParams, out outParams)
    {
    	<Blob> myInf = new Blob(function(){
    		       data : [
    				{
        			               type: image,
    				        size: 100,
    					bg: transparent
    				)
    			      ]
    			})
    			
    	run process_img(){
    		this.myInf.blobToImage({
    			type: jpg
    		})
    	}
    }




***Happy funcode!***
