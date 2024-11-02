**NAMA    : Gilang Bagus Tri Pambudi**                                             
**NIM     : 362358302148**                                                      
**KELAS   : 2A TRPL**
                                                                                    
**PRAKTIKUM**

1. Register User 
Method: POST 
URL: /api/register 
Body (raw JSON):

```
json 
Copy code 
{ 
"name": "Gilang Bagus Tri Pambudi", 
"email": "admin@example.com", 
"password": "gilangtp123" 
}
```

![Screenshot 1](https://github.com/user-attachments/assets/52876962-5584-4044-829c-6b6c87e829f3)


2. Login User 
Method: POST 
URL: /api/login 
Body (raw JSON):

```
json 
Copy code 
{ 
"name": "Gilang Bagus Tri Pambudi", 
"password": "gilangtp123" 
}
 ```

![Screenshot 2](https://github.com/user-attachments/assets/1d200de7-20de-4cb9-b4c2-3988536e73ed)


3. Menyimpan Data Mahasiswa (POST) 
URL: /api/mahasiswas 
Method: POST 
Header:

```
makefile 
Copy code 
Authorization: Bearer <token>
```

Body (raw JSON):

```
Copy code 
{ 
"nama": "Gilang Bagus Tri Pambudi", 
"nim": "362358302148", 
"jurusan": "Teknik Informatika" 
}
```

![Screenshot 3](https://github.com/user-attachments/assets/ea9f63e1-e01b-4830-b838-3c953fd989f9)


4. Mengambil Semua Data Mahasiswa (GET) 
URL: /api/mahasiswas 
Method: GET 
Header:

```
makefile 
Copy code 
Authorization: Bearer <token>
```

![Screenshot 4](https://github.com/user-attachments/assets/aace3e0c-0aac-4901-b41b-e133b4438e60)


Menghapus Data Mahasiswa (Hanya Admin - DELETE) 
URL: /api/mahasiswas/{id} 
Method: DELETE 
Header:

```
makefile 
Copy code 
Authorization: Bearer <token>
```

![Screenshot 5](https://github.com/user-attachments/assets/85b1afb2-989f-4581-acf9-08bb6008cc6d)

