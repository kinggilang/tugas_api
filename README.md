**NAMA    : Alfha Risqi Wicaksono**                                             
**NIM     : 362358302145**                                                      
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
"name": "Alfha Risqi Wicaksono", 
"email": "alfha@mail.com", 
"password": "alfhatampan123" 
}
```

![Screenshot 2024-11-02 144439](https://github.com/user-attachments/assets/0ad4e9c1-1a9e-4e12-8f04-f55969639b09)

2. Login User 
Method: POST 
URL: /api/login 
Body (raw JSON):

```
json 
Copy code 
{ 
"email": "admin@example.com", 
"password": "password123" 
} 
 ```

![Screenshot 2024-11-02 144611](https://github.com/user-attachments/assets/89292a3c-7aa3-41b3-984f-7742316b7ac8)

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
"nama": "Budi Santoso", 
"nim": "12345678", 
"jurusan": "Teknik Informatika" 
}
```

![Screenshot 2024-11-02 145134](https://github.com/user-attachments/assets/a40107a4-d3ce-478d-9456-2c2136731ec6)

4. Mengambil Semua Data Mahasiswa (GET) 
URL: /api/mahasiswas 
Method: GET 
Header:

```
makefile 
Copy code 
Authorization: Bearer <token>
```

![Screenshot 2024-11-02 145157](https://github.com/user-attachments/assets/b6d5ddc2-4d5b-4a32-aec2-70e894bc1a0e)

Menghapus Data Mahasiswa (Hanya Admin - DELETE) 
URL: /api/mahasiswas/{id} 
Method: DELETE 
Header:

```
makefile 
Copy code 
Authorization: Bearer <token>
```

![Screenshot 2024-11-02 145242](https://github.com/user-attachments/assets/6a0f3769-7cce-47a7-bbdc-336be8f2dfb5)
