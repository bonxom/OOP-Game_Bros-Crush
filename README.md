# Bros || Crush 🎮

<div align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/libGDX-E74C3C?style=for-the-badge&logo=gradle&logoColor=white" alt="libGDX">
  <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white" alt="Gradle">
</div>

## 📖 Giới thiệu

**Bros || Crush** là một trò chơi 2D platform adventure được phát triển như đồ án môn Lập trình Hướng đối tượng (OOP) tại Đại học Bách Khoa Hà Nội. 

Trong game, người chơi sẽ vào vai **Chính** - một sinh viên đại học dũng cảm, phải vượt qua nhiều thử thách và đối đầu với vô số quái vật để giải cứu công chúa **Linh** khỏi bàn tay của phù thủy độc ác **Eyesightasu**. 

Điểm đặc biệt của game là cốt truyện sáng tạo với kết thúc mở: sau khi chiến thắng boss ở màn cuối, người chơi sẽ phải đối diện với lựa chọn khó khăn giữa việc giải cứu công chúa Linh hay ba người bạn thân đã hy sinh trong hành trình.

## ✨ Tính năng chính

- 🗺️ **4 màn chơi đa dạng** với độ khó tăng dần
- 👹 **Nhiều loại quái vật** với hành vi và khả năng tấn công khác nhau:
  - Goblin
  - Skeleton
  - Mushroom
  - Flying Eye
  - Orc
  - Boss cuối cùng với các kỹ năng đặc biệt
- ⚔️ **Hệ thống chiến đấu** với nhiều combo tấn công
- 💖 **Thanh máu (Health Bar)** cho nhân vật và enemy
- 🎁 **Hệ thống vật phẩm và rương báu**
- 🔥 **Bẫy và chướng ngại vật** như lava, spike traps
- 🎵 **Âm thanh và hiệu ứng** sống động
- 📜 **Cốt truyện hấp dẫn** với kết thúc mở đa dạng
- 🎨 **Đồ họa 2D pixel art** đẹp mắt và mượt mà

## 🎮 Cách chơi

### Điều khiển

- **← →** hoặc **A D**: Di chuyển trái/phải
- **Space** hoặc **W**: Nhảy
- **J** hoặc **Left Click**: Tấn công
- **K**: Kỹ năng đặc biệt
- **ESC**: Tạm dừng game

### Mục tiêu

1. Vượt qua các màn chơi bằng cách tiêu diệt quái vật và tránh bẫy
2. Thu thập vật phẩm từ rương để tăng sức mạnh
3. Đánh bại boss ở màn cuối
4. Đưa ra lựa chọn cuối cùng về số phận của các nhân vật

## 🛠️ Công nghệ sử dụng

- **Ngôn ngữ lập trình**: Java
- **Game Framework**: [libGDX](https://libgdx.com/) - Framework mạnh mẽ cho phát triển game đa nền tảng
- **Build Tool**: [Gradle](https://gradle.org/)
- **Map Editor**: Tiled Map Editor
- **Design Patterns**: 
  - Singleton Pattern (GameManager, UIManager)
  - Observer Pattern (WorldContactListener)
- **Kỹ thuật OOP**:
  - Tính kế thừa (Inheritance)
  - Tính đóng gói (Encapsulation)
  - Tính trừu tượng (Abstraction)
  - Tính đa hình (Polymorphism)

## 📦 Cấu trúc dự án

```
├── core/                 # Module chính chứa logic game
│   ├── manager/         # Quản lý các thành phần cốt lõi
│   ├── scenes/          # Quản lý hiển thị thanh máu
│   ├── screens/         # Các màn hình game
│   ├── sprites/         # Nhân vật, enemy, items, weapons
│   ├── tools/           # Âm thanh, va chạm, tương tác
│   └── UI/              # Giao diện người dùng
├── lwjgl3/              # Platform desktop
└── assets/              # Tài nguyên (sprites, maps, audio)
```

## 🚀 Hướng dẫn chạy game

### Yêu cầu hệ thống

- Java Development Kit (JDK) 11 hoặc cao hơn
- Gradle (đã bao gồm wrapper)

### Chạy game

**Linux/Mac:**
```bash
./gradlew lwjgl3:run
```

**Windows:**
```bash
gradlew.bat lwjgl3:run
```

### Build file JAR

```bash
./gradlew lwjgl3:jar
```

File JAR sẽ được tạo tại `lwjgl3/build/libs/`

## 🎥 Video Demo

👉 [Xem video demo trên YouTube](https://youtu.be/_yIsIZmzkaY?si=Oo7Q2V0iPWRNlICT)

## 👥 Nhóm phát triển

**Nhóm 15 - Lớp 153989**

| MSSV | Họ và tên | Vai trò |
|------|-----------|---------|
| 20235044 | Nguyễn Quang Đức | Nhóm trưởng - Base code, UI|
| 20235023 | Lê Đức Chính | Màn 2, Health Bar, Logic công chúa |
| 20235036 | Trần Gia Định | Màn 1, Logic cơ bản, Báo cáo |
| 20235004 | Nguyễn Bá Đức Anh | Màn 4 (Boss), Slide thuyết trình |
| 20235050 | Hồ Minh Dũng | Màn 3, Logic va chạm, Player movement, Map loading, Merge code |

**Giáo viên hướng dẫn**: Trần Nhật Hoá

## 📄 Giấy phép

Dự án được phát triển cho mục đích học tập tại Trường Công nghệ Thông tin và Truyền thông - Đại học Bách Khoa Hà Nội.

---

<div align="center">
  Made with ❤️ by Team 15
</div>
