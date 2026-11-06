# Bùi Văn Đức

**Automation Team Leader @ STI-VietNam** | **Creator @ [DBI - Data Bridge Industrial](https://dbivn.com/) & ACS (AGV Control System)**

- **Website:** [dbivn.com](https://dbivn.com/)
- **Email:** [buiminhduc23011@gmail.com](mailto:buiminhduc23011@gmail.com)
- **Phone:** [0963 322 515](tel:0963322515)
- **Facebook:** [buivanduc.use](https://www.facebook.com/buivanduc.use)
- **Location:** Việt Nam

---

### Giới thiệu

Kỹ sư Tự động hóa và Kiến trúc sư Phần mềm Công nghiệp với hơn 5 năm kinh nghiệm thực chiến trong việc thiết kế, xây dựng và triển khai các hệ thống điều hành xe tự hành AGV, thị giác máy tính, máy tự động hóa và giải pháp chuyển đổi số sản xuất (IIoT / Industry 4.0).

Phần lớn các giải pháp điều khiển, phần mềm máy và mã nguồn hệ thống thực tế được triển khai và bảo mật trong các **Private Repositories** của doanh nghiệp và đối tác.

---

### Hai nền tảng trọng tâm

#### 1. ACS - AGV Control System & Fleet Simulation
Hệ sinh thái điều phối, quy hoạch tuyến đường và mô phỏng giao thông cho đội xe tự hành AGV trong nhà máy thông minh:
- **[ACS.Simulation](https://github.com/buiminhduc23011/ACS.Simulation):** Mô phỏng bài toán điều phối, tính toán quỹ đạo và giải quyết xung đột giao thông (traffic control) thời gian thực.
- **Kiến trúc công nghệ:**
  - `ACS.Geometry`: Thư viện toán hình học tính toán quỹ đạo, góc lái và tọa độ di chuyển.
  - `ACS.Simulator.API`: Backend .NET C#, tích hợp SignalR truyền dữ liệu telemetry hai chiều thời gian thực.
  - `acs.simulator.web`: Giao diện web giám sát (React, TypeScript, Ant Design, Zustand, Recharts, Virtual Joystick).
  - Đồng bộ trọn gói với HMI trên xe (`sti-lift-agv-hmi`) và bộ cấu hình (`sti-agv-config`).

#### 2. DBI - Data Bridge Industrial
Nền tảng Gateway công nghiệp và cầu nối dữ liệu OT/IT: [https://dbivn.com/](https://dbivn.com/)
- **Giao thức & Kết nối PLC:** Siemens S7 (S7-1200/1500), Mitsubishi (FX/Q Series qua McProtocol), Omron (FINS), Delta, Modbus RTU/TCP, OPC UA.
- **Kiến trúc hệ thống:**
  - `DBI.Runtime`: Core runtime động cơ xử lý và điều phối dữ liệu.
  - `DBI.Drivers` & `DBI.DataRelay`: Giao tiếp driver đa thiết bị và chuyển tiếp dữ liệu thời gian thực.
  - `DBI.SoftPLC`: Phần mềm điều khiển trực tiếp trên môi trường máy tính công nghiệp (IPC).
  - `DBI.VisionKit`: Tích hợp xử lý ảnh công nghiệp.
  - `DBI.CommTest` & `DBI.Server-Releases`: Công cụ kiểm thử đường truyền và đóng gói sản phẩm.

---

### Năng lực chuyên môn

#### 1. Hệ thống AGV, Robot & Thị giác máy tính
- Thuật toán điều phối và quản lý đội xe tự hành AGV (Traffic Management, Fleet Control, Dispatching).
- Phần mềm điều khiển, giao diện HMI và cấu hình tham số xe tự hành AGV (Lifting AGV, Tugger AGV).
- Tích hợp hệ thống Machine Vision công nghiệp: Keyence CV-X Series, camera công nghiệp giao tiếp C# qua Ethernet.
- Điều khiển cánh tay robot và truyền thông Modbus/TCP, CAN bus.

#### 2. Tự động hóa & Máy công nghiệp
- Lập trình PLC: Siemens, Mitsubishi, Delta, Omron.
- Thiết kế hệ thống điều khiển máy chuyên dụng: Máy cắt rotor nội suy, máy dán băng dính keo, máy ép servo.
- Hệ thống kho tự động Rotary Warehouse và giải pháp truyền tải phôi công nghiệp.

#### 3. IIoT & Phát triển phần mềm
- Ngôn ngữ & Nền tảng: C# (.NET, WPF, SignalR), C, C++, TypeScript/React, Python, Node.js.
- Giao thức truyền thông: Modbus RTU/TCP, OPC UA, MC Protocol, FINS, OCPP 1.6J (trạm sạc xe điện).
- Hệ thống nhúng vi điều khiển: STM32, ESP32, ESP8266, FreeRTOS.

---

### GitHub Activity & Contributions

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=buiminhduc23011&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=buiminhduc23011&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="48%" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=buiminhduc23011&theme=tokyonight&hide_border=true" width="97%" alt="GitHub Streak" />
</p>
