### SELECT SORGUSU
```SELECT * FROM CUSTOMERLIST```
Bu komutla CUSTOMERLIST tablosundaki **tüm elemanlar** gelir. Bunun sebebi 'SELECT' anahtar kelimesinden sonra kullanılan **\*** ifadesidir.

### INSERT INTO SORGUSU
``INSERT INTO CUSTOMERLIST VALUES DEGER1,DEGER2,DEGER3``
Bu komutla CUSTOMERLIST tablosuna DEGER1, DEGER2 VE DEGER3 eklenmiş olur.

### UPDATE SORGUSU
``` UPDATE CUSTOMER SET AGE=DATEDIFF(YEAR,BIRTHDAY,GETDATE)  ```
Bu komutla CUSTOMER kaydının Age özelliği değiştirilmiştir. 

### DELETE SORGUSU
```DELETE FROM CUSTOMER ```
Bu komutla bir tablodaki değer silinir.
