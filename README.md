# Baraction.sh สำหรับ Spectrwm (BlackArch Linux)  

![showcase](https://raw.githubusercontent.com/bunnyhop-dev/baraction/refs/heads/main/2025-05-13-010328_1920x1080_scrot.png)

## คำอธิบาย  
`baraction.sh` เป็นสคริปต์ที่ใช้แสดงข้อมูลสถานะต่างๆ บนแถบสถานะของ Spectrwm เช่น การใช้ CPU, RAM, อุณหภูมิ ฯลฯ  

## วิธีใช้งาน  
1. คัดลอกไฟล์ `baraction.sh` ไปยังไดเรกทอรีที่คุณต้องการ เช่น `~/.config/spectrwm/`  
2. เปิดไฟล์ `~/.spectrwm.conf` แล้วเพิ่มบรรทัดนี้:  
   ```plaintext
   bar_action = ~/your/baraction/path.sh
3. รีโหลด Spectrwm `Mod+Q`

# Baraction.sh for Spectrwm (BlackArch Linux)

## Description
`baraction.sh` is a script used to display system status information on Spectrwm's status bar, such as CPU usage, RAM usage, temperature, etc.

## Usage
1. Copy the `baraction.sh` file to an appropriate directory, e.g ~/.config/spectrwm/
2. Open `~/.spectrwm.conf` and add this line
   ```plaintext
   bar_action = ~/your/baraction/path.sh
3. Reload Spectrwm `Mod+Q`
