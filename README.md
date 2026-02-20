# Projects — Zhugez Portfolio Hub

> Central home for active builds, production systems, and security/AI engineering projects by **zhugez**.

[![Portfolio Hub](https://img.shields.io/badge/Projects-Hub-111827?style=for-the-badge)](https://github.com/zhugez/Projects)

---

## ⚡ Quick Links

- Aletheia: https://github.com/zhugez/Aletheia
- Codexible: https://github.com/zhugez/Codexible
- Codexible Live: https://codexible.vercel.app
- VerTel Bot: https://github.com/zhugez/vertelt-bot
- Abyss: https://github.com/zhugez/Abyss
- ArcStrike: https://github.com/zhugez/ArcStrike
- ShadeHunter: https://github.com/zhugez/ShadeHunter
- Ryuu: https://github.com/zhugez/ryuu
- ExoMind: https://github.com/zhugez/ExoMind
- Mycelium: https://github.com/zhugez/Mycelium

---

## 📊 Project Status Board

| Project | Category | Status | Link |
|---|---|---|---|
| Aletheia | AI / RAG Platform | 🟢 Active | https://github.com/zhugez/Aletheia |
| Codexible | LLM API Platform | 🟢 Active | https://github.com/zhugez/Codexible |
| VerTel Bot | C++ Framework | 🟢 Active | https://github.com/zhugez/vertelt-bot |
| Abyss | AppSec Platform | ✅ Done | https://github.com/zhugez/Abyss |
| ArcStrike | Security Platform | 🚧 Doing | https://github.com/zhugez/ArcStrike |
| ShadeHunter | Security / Recon | 🚧 Doing | https://github.com/zhugez/ShadeHunter |
| Ryuu | Bot / Infra | 🟢 Active | https://github.com/zhugez/ryuu |
| ExoMind | Knowledge Runtime | 🟢 Active | https://github.com/zhugez/ExoMind |
| Mycelium | WordPress Plugin Intelligence | 🟢 Active | https://github.com/zhugez/Mycelium |

---

## 🧾 HR-Oriented Project Summaries (Objective Format)

### 1) Aletheia (AI / RAG Platform)
- **Bối cảnh/Mục tiêu:** Xây nền tảng hỏi đáp tài liệu có citation cho kho tài liệu lớn.
- **Vai trò:** Kiến trúc + backend + triển khai.
- **Việc đã làm:** Thiết kế modular monolith (API + worker + queue), xây ingest pipeline (chunking + OpenSearch/Qdrant), triển khai hybrid retrieval (BM25 + vector), tối ưu Docker Compose/Dokploy + healthcheck + migration.
- **Kết quả:** Hệ thống chạy end-to-end, có benchmark retrieval, hỗ trợ background jobs và caching.

### 2) Codexible (LLM API Platform)
- **Bối cảnh/Mục tiêu:** Cung cấp lớp API cho tích hợp mô hình LLM/agent.
- **Vai trò:** Product engineering + release/deploy.
- **Việc đã làm:** Duy trì production deployment, chuẩn hóa release/rollback, tăng độ ổn định API và khả năng tích hợp.
- **Kết quả:** Nền tảng hoạt động liên tục với chu trình phát hành rõ ràng.

### 3) VerTel Bot (C++ Framework)
- **Bối cảnh/Mục tiêu:** Xây framework Telegram theo hướng library-first bằng C++.
- **Vai trò:** Thiết kế kiến trúc + xây core framework.
- **Việc đã làm:** Thiết kế module tái sử dụng, thiết lập build/package/docs, tách core library khỏi app-specific logic.
- **Kết quả:** Có nền tảng framework C++ dùng lại được, sẵn cho mở rộng.

### 4) Abyss (AppSec Platform) — Done
- **Bối cảnh/Mục tiêu:** Nền tảng phân tích AppSec local-first.
- **Vai trò:** Hoàn thiện và ổn định nền tảng.
- **Việc đã làm:** Hoàn thiện stack triển khai + hardening, chuẩn hóa pattern để tái sử dụng.
- **Kết quả:** Dự án hoàn thành; nhiều pattern được tái dùng ở Aletheia.

### 5) ArcStrike (Security Platform) — Doing
- **Bối cảnh/Mục tiêu:** Xây nền tảng bảo mật theo hướng vận hành thực tế.
- **Vai trò:** Builder chính trong phase phát triển.
- **Việc đã làm:** Phát triển kiến trúc và các tính năng cốt lõi.
- **Kết quả hiện tại:** Active development.

### 6) ShadeHunter (Security / Recon) — Doing
- **Bối cảnh/Mục tiêu:** Công cụ phục vụ security và recon workflow.
- **Vai trò:** Builder chính.
- **Việc đã làm:** Triển khai các thành phần nền tảng.
- **Kết quả hiện tại:** Active development.

### 7) Ryuu (Bot / Infra)
- **Bối cảnh/Mục tiêu:** Bot/infrastructure phục vụ automation.
- **Vai trò:** Developer chính.
- **Việc đã làm:** Xây và duy trì các thành phần bot/infrastructure.
- **Kết quả:** Dự án đang active.

### 8) ExoMind (Knowledge Runtime)
- **Bối cảnh/Mục tiêu:** Runtime tri thức tích hợp cho agent workflow.
- **Vai trò:** Thiết kế và phát triển hệ thống.
- **Việc đã làm:** Xây nền runtime và tổ chức tích hợp với toolchain agent.
- **Kết quả:** Dự án active.

### 9) Mycelium (WordPress Plugin Intelligence for Bug Bounty)
- **Bối cảnh/Mục tiêu:** Hỗ trợ tải và quản lý plugin WordPress phục vụ quy trình bug bounty trên Patchstack.
- **Vai trò:** Xây công cụ và pipeline vận hành.
- **Việc đã làm:** Thiết kế luồng thu thập/tải plugin phục vụ phân tích; chuẩn hóa quy trình test/đối chiếu trong triage; tối ưu thao tác cho use-case nghiên cứu lỗ hổng WordPress.
- **Kết quả:** Tăng tốc quá trình chuẩn bị mẫu plugin cho phân tích và báo cáo bug bounty.

---

## 🗺️ Hub Roadmap

- [x] Project board + objective summaries
- [x] Real repo links + status clarity
- [ ] Add CI/security/deploy badges per project
- [ ] Add weekly “Recent Wins” section

---

## 🤝 Contact

- GitHub: https://github.com/zhugez
