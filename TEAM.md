# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: NhomNhomNhom
- Candidate problem nhóm chọn (1 câu): Người tham gia (tuyển thủ) khó tiếp cận thông tin chính xác, đầy đủ và cập nhật của các giải đấu Esports do CLB XayGame tổ chức.
- Quyết định cuối (Go / Not Yet / No-Go): Go

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Tống Thiên Bảo | 2A202603461 | Trưởng nhóm, domain owner, phụ trách CP3 & CP4 | bato-bato |
| 2 | Nguyễn Quang Hiệp | 2A202603509 | Phụ trách CP5 (Quy trình Before/After & Problem Statement v0) | Hiep Quang |
| 3 | Dương Minh Tân | 2A202603464 | Phụ trách CP6 (Mức can thiệp & Quyết định) | minhtanhehe |
| 4 | Lưu Văn Việt Đức | 2A202603445 | Phụ trách CP4 (Research) | |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Tống Thiên Bảo | Nhóm | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Tống Thiên Bảo | Nhóm | Assumption map, snapshot hoặc survey |
| CP4 — Research | Lưu Văn Việt Đức | Nhóm | Bảng research có link |
| CP5 — Quy trình trước/sau | Nguyễn Quang Hiệp | Nhóm | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Nguyễn Quang Hiệp | Nhóm | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Dương Minh Tân | Nhóm | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Dương Minh Tân | Nhóm | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### NguyenQuangHiep-2A202603509

**Phần việc phụ trách:**
- Phụ trách chính CP5: Xây dựng Quy trình trước/sau (Before/After) và soạn thảo Problem Statement v0.
- Đề xuất kiến trúc kỹ thuật phân tầng: Rule (Menu FAQ) $\rightarrow$ Rule Cache (gắn mã băm hash Thể lệ) $\rightarrow$ Workflow AI (RAG trích xuất có dẫn nguồn) $\rightarrow$ Con người (HITL - Human-in-the-Loop).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):
- Thiết kế 2 sơ đồ Mermaid chi tiết cho quy trình hiện tại (bóc tách 7 bước kèm thời gian, chỉ ra bottleneck 15–30 phút ở khâu chờ BTC) và quy trình tương lai.
- Lập bảng Before/After định lượng cụ thể: rút ngắn thời gian từ 40–55' xuống dưới 2', giảm thao tác thủ công từ 6/7 xuống 1.
- Soạn thảo Problem Statement v0 hoàn chỉnh gồm 6 trường cốt lõi (Actor, Quy trình, Bottleneck, Impact, Success Metric có baseline/target rõ ràng, Boundary an toàn cho AI) và ghi nhận phản biện giải pháp.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):
- Mục 4 (Quy trình trước/sau - CP5) và Mục 5 (Problem Statement v0 - CP5) trong `report/team/group_report.md`.
- Mục 4 và Mục 6 trong `report/individual/2A202603509_NguyenQuangHiep.md`.

**Điều mình học được từ phần nhóm:**
- Hiểu được sự khác biệt giữa "nghĩ ra giải pháp trước" (solution-first) và "bóc tách quy trình thực tế để tìm điểm nghẽn".
- Nắm vững cách phân tầng công nghệ: không phải bài toán nào cũng cần nhảy ngay vào Agent hay AI phức tạp, mà nên tận dụng tối đa No AI và Rule để tối ưu chi phí và độ tin cậy trước khi tích hợp AI Workflow.
