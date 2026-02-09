HomeLab - Windows Server 2016 + Windows 10 (Hyper-V)

Projekt domowego laboratorium w celu nauki administracji systemami Windows. Utworzyłem środowisko wirtualne w Hyper-V na moim komputerze osobistym z systemem Windows 10 Pro, składające się z serwera Windows Server 2016 oraz maszyn klienckich Windows 10.

1. Konfiguracja Hyper-V:
- utworzenie maszyn oraz dysków wirtualnych
- przydzielenie zasobów procesora/pamięci
- utworzenie wirtualnych kart sieciowych

Serwer posiada 2 karty sieciowie, jedną w trybie pracy NAT, aby miał dostęp do internetu, druga karta pracuje w sieci wewnętrznej. Klient posiada tylko jedną kartę sieciową w sieci wewnętrznej, jak na razie nie ma dostępu do internetu.

<img width="235" height="369" alt="image" src="https://github.com/user-attachments/assets/0ebe51d9-fd30-4bca-8461-67fddce89264" />

<img width="240" height="323" alt="image" src="https://github.com/user-attachments/assets/b55f4f28-88e3-4522-a85c-fc6d4ebcc9e6" />

<img width="558" height="271" alt="image" src="https://github.com/user-attachments/assets/9838d895-d1a9-46c1-a398-6ca13749d159" />

2. Instalacja systemów:
- Windows Server 2016
- Windows 10 Pro

<img width="638" height="479" alt="image" src="https://github.com/user-attachments/assets/123842ac-d130-4838-bd8a-81360001d94b" />

<img width="635" height="475" alt="image" src="https://github.com/user-attachments/assets/da642532-2893-4608-a088-aa0cb27c0f10" />

3. Konfiguracja serwera:
- zmiana nazwy administratora i wyłączenie domyślnego konta admina
- ustawienie adresu ip

<img width="374" height="383" alt="image" src="https://github.com/user-attachments/assets/2f39a0c0-c9b3-4bea-ab3c-e6ca0f7417e9" />

<img width="524" height="393" alt="image" src="https://github.com/user-attachments/assets/0c8091c6-1896-44d8-bd51-a30ae4a3e00b" />

<img width="377" height="223" alt="image" src="https://github.com/user-attachments/assets/31022b48-fc97-4d04-b95b-367616c63904" />

<img width="395" height="449" alt="image" src="https://github.com/user-attachments/assets/db019065-c02f-4f80-acc2-609c097cc9f6" />

4. Konfiguracja klienta:
- ustawienie adresu ip, bramy domyślnej, serwera DNS
- test połączenia z serwerem

<img width="396" height="449" alt="image" src="https://github.com/user-attachments/assets/39e46f89-580c-4df0-a036-7bf71f03ed07" />
<img width="455" height="210" alt="image" src="https://github.com/user-attachments/assets/ce5944a4-6115-4054-841e-9820fa505c97" />

5. Active Directory:
- Instalacja
- Tworzenie lasu i domeny
- Jednostki organizacyjne, grupy, dodawanie użytkowników
- Profil mobilny
- Udostępnienie zasobu dyskowego


<img width="749" height="454" alt="image" src="https://github.com/user-attachments/assets/1ce5dfbd-25c0-4487-ba52-4ce911d9399f" />

<img width="432" height="170" alt="image" src="https://github.com/user-attachments/assets/4c9e384a-8a20-474d-ae66-df04d82b619d" />

<img width="439" height="218" alt="image" src="https://github.com/user-attachments/assets/0cee9d28-f0bb-47a4-86b6-edcf893ee99a" />

<img width="418" height="531" alt="image" src="https://github.com/user-attachments/assets/9f19d205-8b9a-4953-9042-39a5d84318bf" />














