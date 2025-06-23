# Lộ trình học SOC Analyst trong 12 tuần

Chào bạn, tôi đã xem qua lộ trình (roadmap) SOC Analyst mà mentor đã gửi cho bạn. Đây là một lộ trình rất chi tiết và đầy đủ, bao quát hầu hết các mảng kiến thức và kỹ năng quan trọng.

Để hoàn thành lộ trình này, bạn sẽ cần sự tập trung và kiên trì. Dựa trên lịch học bạn đưa ra (buổi tối các ngày 2, 3, 4 và cả ngày cho 5, 6, 7, Chủ Nhật), tôi đã xây dựng một kế hoạch học tập chi tiết trong **12 tuần**. Kế hoạch này cân bằng giữa việc học lý thuyết và thực hành (lab), giúp bạn nắm vững kiến thức một cách hiệu quả nhất.

Dưới đây là lịch trình đề xuất:

---

### **Giai đoạn 1: Nền tảng và SIEM (Tuần 1-2)**

Mục tiêu của giai đoạn này là xây dựng kiến thức cốt lõi về an ninh mạng và làm chủ các khái niệm cơ bản về SIEM, công cụ trung tâm của một SOC Analyst.

*   **Tuần 1: Security Fundamentals & SIEM Concepts**
    *   **Thứ 2 (Tối):** *Nghỉ hoặc tự ôn tập*
    *   **Thứ 3 (Tối):** Tổng quan về SOC. Ôn lại kiến thức Mạng máy tính cơ bản (TCP/IP, DNS, HTTP/S).
    *   **Thứ 4 (Tối):** Nguyên tắc bảo mật (Security Principles): CIA Triad, AAA.
    *   **Thứ 5 (Tối):** Nguyên tắc bảo mật: Least Privilege, Defense in Depth.
    *   **Thứ 6 (Cả ngày):** Quản lý rủi ro (Risk Management) & Vòng đời ứng cứu sự cố (Incident Response Lifecycle).
    *   **Thứ 7 (Cả ngày):** SIEM Concepts: Kiến trúc, Thu thập và Tổng hợp Log (Log Collection & Aggregation).
    *   **CN (Cả ngày):** SIEM Concepts: Chuẩn hóa Log (Normalization), Phân tích (Parsing), và Tương quan sự kiện (Event Correlation).

*   **Tuần 2: SIEM Deep Dive & Lab**
    *   **Thứ 3 (Tối):** SIEM: Tạo cảnh báo (Alerting) và Sự cố (Incident Generation).
    *   **Thứ 4 (Tối):** **Lab:** Cài đặt một SIEM mã nguồn mở (Wazuh hoặc Security Onion).
    *   **Thứ 5 (Tối):** **Lab:** Cấu hình thu thập log từ Windows/Linux và các thiết bị mạng.
    *   **Thứ 6 (Cả ngày):** Phát triển Use Case cho SIEM: Xây dựng luật phát hiện (Detection Rules).
    *   **Thứ 7 (Cả ngày):** Phát triển Use Case cho SIEM: Tạo các tìm kiếm tương quan (Correlation Searches) và Tinh chỉnh cảnh báo (Tuning Alerts).
    *   **CN (Cả ngày):** **Lab:** Viết một vài luật và correlation search đơn giản trên SIEM đã cài đặt.

---

### **Giai đoạn 2: Phân tích Dữ liệu và Threat Intelligence (Tuần 3-5)**

Giai đoạn này tập trung vào kỹ năng phân tích dữ liệu và sử dụng thông tin tình báo về mối đe dọa (Threat Intelligence) để làm giàu ngữ cảnh cho các cảnh báo.

*   **Tuần 3: Data Analysis for Security**
    *   **Thứ 3 (Tối):** Data Analysis: Các loại dữ liệu, cấu trúc dữ liệu và kỹ thuật khai phá dữ liệu.
    *   **Thứ 4 (Tối):** Giới thiệu Python cho phân tích dữ liệu (Pandas, Numpy).
    *   **Thứ 5 (Tối):** **Lab:** Dùng Python (Pandas) để đọc và phân tích các file log (web server, firewall).
    *   **Thứ 6 (Cả ngày):** Machine Learning Basics: Các khái niệm cơ bản và ứng dụng trong an ninh mạng.
    *   **Thứ 7 (Cả ngày):** Python for Machine Learning: Giới thiệu Scikit-learn.
    *   **CN (Cả ngày):** **Lab:** Thử nghiệm các mô hình ML đơn giản để phát hiện bất thường trên bộ dữ liệu mẫu.

*   **Tuần 4: Threat Intelligence (Part 1)**
    *   **Thứ 3 (Tối):** Threat Intelligence (TI) Fundamentals: Định nghĩa, các loại (Strategic, Tactical, Operational).
    *   **Thứ 4 (Tối):** TI: Các tác nhân đe dọa (Threat Actors) và động cơ của chúng.
    *   **Thứ 5 (Tối):** TI: Vòng đời Threat Intelligence (Lifecycle).
    *   **Thứ 6 (Cả ngày):** Các nguồn TI (Opensource, Enterprise) và các nền tảng TI (TIPs).
    *   **Thứ 7 (Cả ngày):** OSINT và Dark Web Monitoring: Khái niệm và công cụ.
    *   **CN (Cả ngày):** **Lab:** Sử dụng các công cụ OSINT (VirusTotal, Shodan, a-z.tools) để thu thập thông tin.

*   **Tuần 5: Threat Intelligence (Part 2)**
    *   **Thứ 3 (Tối):** Phân tích TI: IOCs, Phân tích báo cáo về mối đe dọa.
    *   **Thứ 4 (Tối):** Phân tích TI: Tương quan dữ liệu, làm giàu thông tin (Enrichment).
    *   **Thứ 5 (Tối):** Các chuẩn chia sẻ TI: STIX/TAXII.
    *   **Thứ 6 (Cả ngày):** Nền tảng chia sẻ TI: Giới thiệu MISP.
    *   **Thứ 7 (Cả ngày):** **Lab:** Tích hợp các nguồn Threat Intel feed vào SIEM của bạn.
    *   **CN (Cả ngày):** **Lab:** Dùng thông tin từ TI để điều tra lại các cảnh báo đã có trong SIEM.

---

### **Giai đoạn 3: Phòng thủ và Điều tra (Tuần 6-9)**

Tập trung vào các kỹ năng thực chiến như quản lý lỗ hổng, săn tìm mối đe dọa và phân tích mã độc.

*   **Tuần 6: Vulnerability Management**
    *   **Thứ 3 (Tối):** Khái niệm Quản lý lỗ hổng: CVE, Methodologies.
    *   **Thứ 4 (Tối):** Các công cụ quét lỗ hổng (Vulnerability Scanning Tools) như Nessus, OpenVAS.
    *   **Thứ 5 (Tối):** **Lab:** Cài đặt và sử dụng OpenVAS để quét một vài máy ảo trong lab.
    *   **Thứ 6 (Cả ngày):** Phân tích kết quả quét, báo cáo (Reporting) và quy trình quản lý bản vá (Patch Management).
    *   **Thứ 7 (Cả ngày):** Tìm hiểu về các cơ sở dữ liệu khai thác lỗ hổng (Exploit-DB, Metasploit).
    *   **CN (Cả ngày):** **Lab:** Thử tìm kiếm và đọc hiểu về một lỗ hổng cụ thể trên CVE Mitre và Exploit-DB.

*   **Tuần 7: Incident Response & Threat Hunting**
    *   **Thứ 3 (Tối):** Quy trình IR: Nhận diện, Phân loại, Ngăn chặn (Identification, Classification, Containment).
    *   **Thứ 4 (Tối):** Quy trình IR: Loại bỏ, Phục hồi, Rút kinh nghiệm (Eradication, Recovery, Post-Incident Analysis).
    *   **Thứ 5 (Tối):** Phương pháp luận Săn tìm mối đe dọa (Threat Hunting Methodologies).
    *   **Thứ 6 (Cả ngày):** Các công cụ và kỹ thuật Threat Hunting. Phân tích dữ liệu để tìm kiếm bất thường.
    *   **Thứ 7 (Cả ngày):** Tìm hiểu về Endpoint Detection and Response (EDR).
    *   **CN (Cả ngày):** **Lab:** "Đi săn" trên các bộ dữ liệu log có sẵn hoặc trên chính hệ thống lab của bạn.

*   **Tuần 8: Malware Analysis (Static Analysis)**
    *   **Thứ 3 (Tối):** Các loại mã độc (Malware Types).
    *   **Thứ 4 (Tối):** Kỹ thuật phân tích mã độc (Static, Dynamic, Hybrid).
    *   **Thứ 5 (Tối):** Phân tích tĩnh: File Hashing, String Analysis.
    *   **Thứ 6 (Cả ngày):** Phân tích tĩnh: Cấu trúc file PE (PE file analysis).
    *   **Thứ 7 (Cả ngày):** **Lab:** Dùng các công cụ như PEStudio, BinText, Yara để phân tích tĩnh một mẫu mã độc.
    *   **CN (Cà ngày):** Ôn tập và thực hành thêm về phân tích tĩnh.

*   **Tuần 9: Malware Analysis (Dynamic Analysis)**
    *   **Thứ 3 (Tối):** Các khái niệm về Phân tích động.
    *   **Thứ 4 (Tối):** Kỹ thuật Sandbox.
    *   **Thứ 5 (Tối):** **Lab:** Cài đặt môi trường lab an toàn để phân tích động (VM, Flare VM, Remnux).
    *   **Thứ 6 (Cả ngày):** **Lab:** Thực hành phân tích động một mẫu mã độc an toàn trong sandbox.
    *   **Thứ 7 (Cả ngày):** Các họ mã độc (Malware families), các giải pháp Anti-Malware.
    *   **CN (Cả ngày):** Kỹ thuật loại bỏ và khắc phục mã độc (Malware removal and remediation).

---

### **Giai đoạn 4: Nâng cao và Tự động hóa (Tuần 10-12)**

Hoàn thiện kỹ năng với các chủ đề nâng cao và học cách tự động hóa các tác vụ lặp lại.

*   **Tuần 10: Advanced Threat Detection**
    *   **Thứ 3 (Tối):** EUBA: Khái niệm và lợi ích.
    *   **Thứ 4 (Tối):** EUBA: Nguồn dữ liệu, xây dựng hồ sơ hành vi (Behavioral Profiling).
    *   **Thứ 5 (Tối):** Công nghệ đánh lừa (Deception Technology): Honeypots, Decoy systems.
    *   **Thứ 6 (Cả ngày):** **Lab:** Tìm hiểu và thử triển khai một honeypot đơn giản.
    *   **Thứ 7 (Cả ngày):** Phân tích các sự kiện từ môi trường deception.
    *   **CN (Cả ngày):** Ôn tập tổng hợp về các kỹ thuật phát hiện mối đe dọa.

*   **Tuần 11: Automation with Python & SOAR**
    *   **Thứ 3 (Tối):** Python for Security: Các module hữu ích (requests, os, subprocess).
    *   **Thứ 4 (Tối):** **Lab:** Viết script Python để tự động hóa một tác vụ nhỏ (vd: query API của VirusTotal).
    *   **Thứ 5 (Tối):** Giới thiệu về SOAR (Phantom, Shuffle).
    *   **Thứ 6 (Cả ngày):** Tìm hiểu về các hành động tự động (Auto Actions) và tự động hóa bằng Bot (BOT Automation).
    *   **Thứ 7 (Cả ngày):** **Lab:** Tìm hiểu giao diện và cách hoạt động của một nền tảng SOAR (bản community).
    *   **CN (Cả ngày):** Ôn tập và củng cố kiến thức về tự động hóa.

*   **Tuần 12: Reporting & Final Project**
    *   **Thứ 3 (Tối):** Kỹ năng báo cáo và trực quan hóa (Reporting and visualization).
    *   **Thứ 4 (Tối):** Xây dựng Dashboard và Report trong SIEM/SOC.
    *   **Thứ 5 (Tối):** Quản lý cấu hình (Config Management) và xử lý Add-on.
    *   **Thứ 6 (Cả ngày):** **Dự án cuối khóa:** Chọn một kịch bản tấn công (vd: phishing, ransomware) và thực hiện điều tra từ A-Z trên hệ thống lab của bạn.
    *   **Thứ 7 (Cả ngày):** **Dự án cuối khóa:** Viết báo cáo phân tích sự cố chi tiết.
    *   **CN (Cả ngày):** Tổng kết toàn bộ lộ trình, xác định điểm mạnh/yếu và lên kế hoạch cho các bước tiếp theo.

---

### **Lời khuyên thêm:**

*   **Linh hoạt:** Đây là lịch trình tham khảo. Bạn có thể điều chỉnh thời gian cho mỗi chủ đề tùy thuộc vào kiến thức nền và tốc độ học của mình.
*   **Thực hành là vua:** Đừng chỉ đọc lý thuyết. Hãy dành ít nhất 50% thời gian của bạn trong môi trường lab. Việc tự tay cấu hình, tự tay "phá" và "sửa" sẽ giúp bạn nhớ lâu hơn bất kỳ bài giảng nào.
*   **Ghi chép:** Sử dụng các công cụ như Obsidian, Notion, hoặc đơn giản là một cuốn sổ để ghi lại những gì bạn học được mỗi ngày.
*   **Tham gia cộng đồng:** Tham gia các diễn đàn, nhóm Facebook/Zalo về an ninh mạng ở Việt Nam để trao đổi và học hỏi.

Chúc bạn học tốt và sớm hoàn thành mục tiêu trở thành một SOC Analyst giỏi! 
