วิธีใช้:

1. วางไฟล์เหล่านี้ในโฟลเดอร์เดียวกัน:
   - index.html
   - bootloader.bin
   - partitions.bin
   - boot_app0.bin
   - firmware.bin

2. เปิด cmd ในโฟลเดอร์
   python -m http.server 8000

3. เปิด
   http://localhost:8000/index.html

4. กด Flash

*** ถ้าไม่มี boot_app0.bin ให้ลบออกในช่องได้ ***
