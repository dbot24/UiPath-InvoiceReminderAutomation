# Automated Invoice Reminder System 
Automation berbasis **UiPath** yang digunakan untuk membaca dan mengolah data invoice dari file Excel, kemudian mengirimkan email reminder secara otomatis kepada customer berdasarkan alamat email yang tersedia pada data invoice.

Automation ini membantu mengurangi proses manual dalam pengecekan invoice overdue dan pengiriman reminder kepada customer.

# Tujuan utama dari automation ini:
- Membaca data invoice dari file Excel.
- Melakukan pengolahan dan filtering data invoice.
- Mengidentifikasi invoice yang memiliki status **Unpaid**.
- Mengidentifikasi invoice yang memiliki **DaysOverDue > 0**.
- Mengambil alamat email customer dari data Excel.
- Mengirimkan email reminder secara otomatis kepada customer yang memenuhi kriteria.

# Technology
- UiPath Studio
- Excel Activities
- DataTable
- SMTP Email
- VB.NET untuk pengolahan data
