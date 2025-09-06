# Unity 3D Movement
Template simple buat **Movement 3D** di Unity dengan **2 Scene terpisah**:
-  Scene First Person (First Person View)
-  Scene Third Person (Third Person View)
-  Walk / Run
-  Jump
- Camera Mengikuti Player (Third Person View)

Kalian bisa pakai template ini buat belajar dasar FPV & TPV sekaligus, tinggal pilih scene yang mau dijalankan.

---

## Features
- **First Person Mode**:
  - Kontrol WASD + Mouse Look
  - Sprint (Shift)
  - Lompat (Space)
- **Third Person Mode**:
  - Kontrol WASD
  - Sprint (Shift)
  - Lompat (Space)
  - Kamera follow player dengan offset

---

##Setup Project
1. Buat folder `Scenes/` lalu bikin 2 scene:
   - `FirstPCamera`
   - `ThirdPCamera`
2. Buat folder `Scripts/` untuk semua script.
---

##Animator Setup (Untuk TPV)
- Parameter:
  - `float Speed`
  - `bool IsRunning`
  - `bool IsJumping`
- States:
  - Idle
  - Walk
  - Run
  - Jump

> FPS biasanya **tidak pakai animator karakter** (cuma tangan/senjata), jadi animasi lebih simpel.
