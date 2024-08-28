MS Dhoni - ODI Performance Analysis with SQL

Collected Data set from the Kaggle.com

DATA PREPROCESSING
-> Info about the Table 'MSDhoni' which describes the columns and datatypes.
![image](https://github.com/user-attachments/assets/5f9e45eb-2ebc-4005-b506-454e888a9c58)
![image](https://github.com/user-attachments/assets/58e4d314-34e8-4b40-bc49-47f147a48000)

-> Checking Null Values.
![image](https://github.com/user-attachments/assets/3b82218c-e53b-4929-9be1-b313ed86eeee)
![image](https://github.com/user-attachments/assets/27192044-8580-4110-8265-80c2239a9a8a)

-> Display first few rows.
![image](https://github.com/user-attachments/assets/333bc4eb-3213-4318-b78d-fae7818b511a)
![image](https://github.com/user-attachments/assets/346817e4-1cf9-422f-9d19-abbd245e1f12)

-> Column 'Runs' has the symbol * , it indicates the 'Not Out'
![image](https://github.com/user-attachments/assets/e225de88-5075-4377-ae87-f33dc79e9256)
![image](https://github.com/user-attachments/assets/d12856f8-1084-4d4a-bbaa-fb2982ac1cb4)

-> Removing the * symbol
![image](https://github.com/user-attachments/assets/69f0f96d-979e-432a-8c75-4378073b007f)
![image](https://github.com/user-attachments/assets/e122f94f-8cd9-47b9-a221-0e71fcff7d72)
-> All the * symbol are removed from 'Runs'. But need to change the data type to integer since it is in text.
![image](https://github.com/user-attachments/assets/faf7a231-7e48-4e39-82e1-c3085fcedcf9)

-> Changing text datatype to integer.
![image](https://github.com/user-attachments/assets/2f9d6581-e6bc-47f6-b2c2-83fe39163bec)
![image](https://github.com/user-attachments/assets/1ee4fdb0-890a-40f8-8779-570d1f92ed55)

EXPLORATORY DATA ANALYSIS
1. What is MS Dhoni's total number of matches,runs, and average in ODIs?
![image](https://github.com/user-attachments/assets/7fcb59f9-ab12-43dd-90c6-2a44d392dd13)
![image](https://github.com/user-attachments/assets/8bb41151-2bab-4efd-9a9a-d59c291d7dd2)

2. What are Dhoni's top 5 highest scores with his opponents in ODIs?
![image](https://github.com/user-attachments/assets/c6fd57ca-dfab-4e1b-8486-597f7200cda1)
![image](https://github.com/user-attachments/assets/1dcd6ed9-64ad-4a0f-b8d7-3602163e7229)

3. How many Centuries (100+ Runs) and Half-Centuries (50 - 99 Runs) has Dhoni scored in ODIs?
![image](https://github.com/user-attachments/assets/4d581f6f-ea6b-4307-a65a-84a8a1566682)
![image](https://github.com/user-attachments/assets/b200b66e-9968-497f-a982-f7ab7786f506)
![image](https://github.com/user-attachments/assets/2ddc9fe6-4cee-40b2-9275-dc439b8c38b5)
![image](https://github.com/user-attachments/assets/262f1ca7-e37c-481d-b8bb-a7da80ba8656)
![image](https://github.com/user-attachments/assets/72eee30e-0057-4482-8557-4548dffcd689)
![image](https://github.com/user-attachments/assets/e0832ba7-2109-4b97-9fdc-7ebbe17b2f37)

4. How may matches Dhoni entered as No.7 Position vs Opposition?
![image](https://github.com/user-attachments/assets/16333f90-3c19-42fd-9ee8-56a31c4b839a)
![image](https://github.com/user-attachments/assets/40cf6080-08fc-4fad-8549-2e0a496c0a6a)
![image](https://github.com/user-attachments/assets/ae8b2d13-4215-4fa8-a10a-662aeb23e79f)
![image](https://github.com/user-attachments/assets/438cc68e-3ea4-4808-a251-a1996292528b)
![image](https://github.com/user-attachments/assets/1190caf8-77f6-44b8-8a5d-c9448f39dd8a)

5. Against which country Dhoni scored most runs?
![image](https://github.com/user-attachments/assets/1055459f-28c9-4bc2-8be0-08ec03348dc7)
![image](https://github.com/user-attachments/assets/fc2d03b8-d581-49ad-8dcb-205291ffe4a7)

6. What is Dhoni's High, Low and Average Strike Rate and How many Sixes, Fours and 100+ Strike Rate Matches?
![image](https://github.com/user-attachments/assets/fb8f114f-c502-48b8-830f-39e437337be2)
![image](https://github.com/user-attachments/assets/8b19a391-3385-4268-9964-a4ee4bd0cc19)

7. At which batting position Dhoni has scored the most runs and order them?
![image](https://github.com/user-attachments/assets/3d01a705-2217-4291-a748-56121fcf3d5a)
![image](https://github.com/user-attachments/assets/0dd40ee5-9c46-4d4a-b9d4-5bb76efa823f)

Craze of Dhoni
