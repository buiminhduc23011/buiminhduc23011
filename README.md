# Bùi Văn Đức

**Automation Team Leader @ STI-VietNam** | **Creator @ [DBI - Data Bridge Industrial](https://dbivn.com/) & ACS (AGV Control System)**

- **Website:** [dbivn.com](https://dbivn.com/)
- **Email:** [buiminhduc23011@gmail.com](mailto:buiminhduc23011@gmail.com)
- **Phone:** [0963 322 515](tel:0963322515)
- **Facebook:** [buivanduc.use](https://www.facebook.com/buivanduc.use)
- **Location:** Việt Nam

---

### Giới thiệu

Kỹ sư Tự động hóa và Phần mềm Công nghiệp với hơn 5 năm kinh nghiệm thiết kế, lập trình và triển khai các hệ thống máy tự động hóa, hệ thống điều hành xe tự hành AGV, thị giác máy tính và giải pháp số hóa nhà máy thông minh (IIoT / Công nghiệp 4.0).

Tác giả và kiến trúc sư hệ thống của hai dự án nền tảng:
- **ACS (AGV Control System & Fleet Simulation):** Hệ sinh thái phần mềm điều phối, mô phỏng tuyến đường và quản lý đội xe tự hành AGV trong nhà máy thông minh.
- **DBI (Data Bridge Industrial):** Nền tảng Gateway công nghiệp kết nối dữ liệu đa tầng giữa OT (phần cứng/PLC) và IT (hệ thống quản lý, giám sát, cloud).

---

### Hai dự án nền tảng tâm huyết

#### 1. ACS - AGV Control System & Fleet Simulation
Hệ sinh thái điều phối và mô phỏng đội xe tự hành AGV chuyên sâu:
- **[ACS.Simulation](https://github.com/buiminhduc23011/ACS.Simulation):** Hệ thống mô phỏng bài toán điều phối, quy hoạch tuyến đường và giải quyết xung đột giao thông (traffic management) thời gian thực cho AGV/AMR.
- **Công nghệ lõi:**
  - `ACS.Geometry`: Thư viện toán hình học tính toán quỹ đạo, góc quay và tọa độ di chuyển.
  - `ACS.Simulator.API`: Backend hiệu năng cao (.NET C#), tích hợp SignalR truyền dữ liệu telemetry hai chiều thời gian thực.
  - `acs.simulator.web`: Giao diện giám sát web hiện đại (React, TypeScript, Ant Design, Zustand, Recharts, Virtual Joystick điều khiển trực tiếp).
  - Kết hợp đồng bộ với phần mềm HMI trên xe (`sti-lift-agv-hmi`) và bộ cấu hình thông số (`sti-agv-config`).

#### 2. DBI - Data Bridge Industrial
Nền tảng Gateway công nghiệp và cầu nối dữ liệu OT/IT: [https://dbivn.com/](https://dbivn.com/)
- **Giao thức & Kết nối PLC:** Siemens S7 (S7-1200/1500), Mitsubishi (FX/Q Series qua McProtocol), Omron (FINS), Delta, Modbus RTU/TCP, OPC UA.
- **Kiến trúc hệ thống:**
  - `DBI.Runtime` & `DBI.Hive`: Core runtime và trung tâm điều phối dữ liệu.
  - `DBI.Drivers` & `DBI.DataRelay`: Giao tiếp driver đa thiết bị và chuyển tiếp dữ liệu thời gian thực.
  - `DBI.SoftPLC`: Phần mềm điều khiển trực tiếp trên môi trường máy tính công nghiệp (IPC).
  - `DBI.VisionKit`: Tích hợp xử lý ảnh công nghiệp.
  - `DBI.CommTest` & `DBI.Server-Releases`: Công cụ kiểm thử đường truyền và đóng gói sản phẩm.

---

### Năng lực chuyên môn

#### 1. Hệ thống AGV, Robot & Thị giác máy tính
- Kiến trúc và thuật toán điều phối đội xe tự hành AGV (Traffic Control, Fleet Management, Dispatching).
- Thiết kế phần mềm điều khiển, HMI và cấu hình cho xe tự hành AGV (Lifting AGV, Tugger AGV).
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

### Dự án tiêu biểu

| Dự án | Công nghệ | Mô tả tóm tắt |
|---|---|---|
| [ACS.Simulation](https://github.com/buiminhduc23011/ACS.Simulation) | .NET, React, TS, SignalR | Hệ thống mô phỏng, điều phối giao thông và quy hoạch tuyến đường cho đội xe AGV/AMR |
| [DBI Ecosystem](https://dbivn.com/) | C#, IIoT, Gateway, OPC UA | Nền tảng Gateway công nghiệp kết nối PLC đa hãng, SoftPLC và phân phối dữ liệu OT/IT |
| [MC-Cut-Via](https://github.com/buiminhduc23011/MC-Cut-Via) | Siemens S7-1200, C# | Phần mềm điều khiển máy tự động cắt rotor nội suy công nghiệp |
| [STI AGV Config & HMI](https://github.com/buiminhduc23011/sti-lift-agv-hmi) | WPF, C#, AGV, Modbus | Giao diện điều khiển HMI và phần mềm cấu hình cho xe tự hành AGV nâng hàng |
| [Keyence CV-X Comm](https://github.com/buiminhduc23011/keyence-cvx-ethernet-communication) | C#, Keyence, Vision | Thư viện C# kết nối Ethernet và điều khiển hệ thống Machine Vision Keyence CV-X |
| [Rotating-Warehouse](https://github.com/buiminhduc23011/Rotating-Warehouse) | PLC, SCADA, Warehouse | Hệ thống quản lý và điều khiển kho hàng thông minh dạng xoay vòng |
| [OCPP 1.6J Charge Simulator](https://github.com/buiminhduc23011/fake-charge-ocpp-protocol1.6J) | IoT, OCPP, EV Charger | Mô phỏng và tích hợp giao thức sạc xe điện chuẩn quốc tế OCPP 1.6J |

Xem thêm danh sách đầy đủ tại **[Repositories](https://github.com/buiminhduc23011?tab=repositories)**.

---

### GitHub Stats

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=buiminhduc23011&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=buiminhduc23011&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="48%" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=buiminhduc23011&theme=tokyonight&hide_border=true" width="97%" alt="GitHub Streak" />
</p>
