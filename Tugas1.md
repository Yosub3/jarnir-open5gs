## Tugas 1: Konektivitas Dasar

### Tanggal: 18 November 2025<br>
### Nama: 
- Satria Angga Wahyunenda
- Yosua Narwastu Karno Misi
### Status K3s: WORKING
<img width="809" height="292" alt="image" src="https://github.com/user-attachments/assets/183a70bb-8daa-48f6-969f-a617135d8a91" />


### gNB Registration
- Status: SUCCESS
- Time taken: 12ms
- AMF Connection: ESTABLISHED
  <img width="806" height="245" alt="image" src="https://github.com/user-attachments/assets/cd444cba-ceed-4b61-9d75-95bdc62878ab" />


### UE Registration
- Status: SUCCESS
- Time taken: 32ms
- IMSI: imsi-001011000000001
- TUN Interface: uesimtun0
- IP Address: 10.45.0.2
<img width="1140" height="490" alt="image" src="https://github.com/user-attachments/assets/f62669fa-3f96-4293-98f8-2aa5c6dd1f47" />


### Connectivity Tests
| Test | Result | RTT (ms) | Photo |
|------|--------|----------|-------|
| UPF Gateway (10.45.0.1) | ✓ PASS | 2.07 (max) | <img width="807" height="240" alt="image" src="https://github.com/user-attachments/assets/5f11ac6e-a6dc-4410-a48a-29e967f7f71c" /> |
| Internet (8.8.8.8) | ✓ PASS | 34.9 (max) | <img width="808" height="248" alt="image" src="https://github.com/user-attachments/assets/b605f723-5576-48f7-af62-8b3ed47873ec" /> |
| DNS Resolution | ✓ PASS | NaN | <img width="799" height="249" alt="image" src="https://github.com/user-attachments/assets/7b47ab64-1d6c-4f72-8584-871d19773c16" /> |
| HTTP/HTTPS | ✓ PASS | Nan | <img width="815" height="502" alt="image" src="https://github.com/user-attachments/assets/a599b64d-c871-4f8e-aa31-c27d1c6a4917" /> |

### Issues Encountered
- Beberap pod pada k3s awalnya tidak bisa running
- mongodb tidak terinstall dengan benar

### Resolution
- Setting IP untuk pod k3s agar pod bisa running
- Setting IP juga pada setting mongoDB karena masih belum mengarah ke IP machine
