# 🏓 Tiêu Chuẩn Mở Cơ Sinh Học & Sa Bàn Chiến Thuật PickleBase 3D (2026)

> 🌐 **Ngôn ngữ / Language:** [**🇻🇳 Tiếng Việt (Hiện tại)**](./README.vi.md) | [**🇺🇸 English (Tiếng Anh)**](./README.md)  
> 🚀 **Cổng Tài Liệu GitHub Pages:** [**Bản Tiếng Việt (`/`)**](https://aizaloapp.github.io/picklebase-open-spec/) | [**Bản Tiếng Anh (`/en/`)**](https://aizaloapp.github.io/picklebase-open-spec/en/)  
> 🏟️ **Nền Tảng Web Chính Thức:** [**https://picklebase.app/**](https://picklebase.app/) ([Phiên bản Quốc tế `/en/`](https://picklebase.app/en/))  
> 🏛️ **Thực Thể Quốc Tế & DOI Khoa Học:** [**Wikidata (Q141814048)**](https://www.wikidata.org/wiki/Q141814048) | [**DOI: 10.5281/zenodo.23582848**](https://doi.org/10.5281/zenodo.23582848) | [**Hugging Face Dataset**](https://huggingface.co/datasets/lekhoa288/picklebase-open-biomechanics)  
> 📦 **Bộ SDK MCP & AI Skill Chính Thức:** [**npm (`picklebase-mcp`)**](https://www.npmjs.com/package/picklebase-mcp) | [**PyPI (`picklebase-mcp`)**](https://pypi.org/project/picklebase-mcp/) | [**ClawHub Registry**](https://clawhub.ai/aizaloapp/skills/picklebase-biomechanics-coach) | [**Chrome Web Store**](https://chromewebstore.google.com/detail/picklebase/fodnbhemeinhfbeomholngiakpbkicjg)

---

## 🎯 1. Tổng Quan & Mục Đích Kho Tiêu Chuẩn Mở

**Học viện Chiến thuật PickleBase (PickleBase Tactical Academy — [picklebase.app](https://picklebase.app/))** công bố kho dữ liệu tiêu chuẩn mở này nhằm chuẩn hóa **thông số cơ sinh học 18 cú đánh**, **phương trình quỹ đạo bóng 3D**, **11 đội hình chiến thuật đánh đôi**, và **giao thức kết nối AI Agent (MCP / OpenAPI 3.1)** dành cho vận động viên, huấn luyện viên và các công cụ tìm kiếm AI.

Toàn bộ dữ liệu được hiệu chuẩn theo **Luật Thi Đấu Chính Thức USA Pickleball 2026** (sân `6.10m × 13.41m`, vùng cấm vô-lê Kitchen NVZ `2.13m / 7ft`, chiều cao lưới tại tâm `86.4cm / 34in`) và kiểm định bởi **HLV Trưởng Nguyễn Văn Khoa (DUPR 5.5)** cùng 3 góc nhìn phân tích video từ **Ben Johns, Tyson McGuffin, Zane Navratil và Jordan Briones**.

---

## 📐 2. Bảng Thông Số Cơ Sinh Học 18 Cú Đánh Cốt Lõi

Bấm vào tên cú đánh bất kỳ bên dưới để mở **Phòng Thí Nghiệm Góc Mặt Vợt 3D & Đồng Hồ Bóng (`<paddle-3d-lab>`)** cùng **3 Góc Nhìn HLV Pro Phụ Đề AI Song Ngữ** trên PickleBase:

| # | Chuyên Đề Kỹ Thuật (Clean URL) | Góc Mặt Vợt 3D & Quỹ Đạo Vung | Điểm Tiếp Xúc Chuẩn | Lực Cầm Vợt & COR | DUPR |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | [**Dink Chéo Sân (4 Biến Thể)**](https://picklebase.app/shot-dink) | `Lift +20° (4h00) • Push +10° (3h20) • Slice +26° (3h45➔5h) • Topspin +4° (3h15➔2h45)` | `Trước mũi chân +30–34cm • Độ cao 45–65cm` | `3.0–4.5/10 (Soft Hands • COR 0.48)` | `2.0–5.5+` |
| 2 | [**Thả Bóng Quả Thứ 3**](https://picklebase.app/shot-third-drop) | `Mở nhẹ +6° đến +12° (Chuẩn +8° • 3h30➔2h45) • Nâng vai +38°` | `Trước mũi chân +36cm • Độ cao 55–70cm` | `4.0/10 (85% Vai • 15% Cổ tay • COR 0.49)` | `3.0+` |
| 3 | [**Tấn Công Tốc Độ (Drive)**](https://picklebase.app/shot-drive) | `Đứng/mở nhẹ 0° đến +4° (Chuẩn +2° • 3h15➔2h30) • Miết +30° kéo lên vai` | `Trước mũi chân +42cm • Đỉnh nảy ngang hông 85cm` | `6.0/10 (85% Vai • 15% Cổ tay • COR 0.53)` | `3.5+` |
| 4 | [**Cú Drip (Hybrid Drive-Drop)**](https://picklebase.app/shot-drip) | `Đứng/mở nhẹ 0° đến +5° (Chuẩn +3° • 3h30➔2h30) • Miết +50° kéo lên vai` | `Trước mũi chân +28cm • Bóng thấp 45–55cm` | `5.0/10 (85% Vai • 15% Cổ tay • COR 0.50)` | `4.0+` |
| 5 | [**Hãm Xung Lực (Reset Shot)**](https://picklebase.app/shot-reset) | `Mở tĩnh +12° đến +20° (Chuẩn +16° • 3h30➔3h45) • Đỡ tĩnh +5°` | `Trước mũi chân +28cm • Độ cao 50–75cm` | `3.0/10 (Bàn tay bọt biển • COR 0.45)` | `3.5+` |
| 6 | [**Vô-lê Xoáy Cuộn (Roll Volley)**](https://picklebase.app/shot-roll-volley) | `Mở nhẹ +4° (0°➔+6° tại 3h15) • Miết dọc lưng bóng 3h15➔2h45 kéo lên vai (+42°)` | `Trước mũi chân +42cm • Dưới lưới 60–78cm` | `5.0/10 (85% Vai • 15% Cổ tay • COR 0.51)` | `4.0+` |
| 7 | [**Tuyệt Kỹ Flick Cổ Tay (Backhand & Forehand Flick)**](https://picklebase.app/shot-flick) | `Khép -8° (82° • Chuẩn -10°➔-5°) • Búng đĩa bay +18° (2h45➔1h40)` | `Trước mặt +45cm • Ngang/trên lưới 86–95cm` | `Xả lỏng 3.5/10 ➔ Búng 8.0/10 (<15cm • COR 0.56)` | `4.0+` |
| 8 | [**Vô-lê Đấm Cận Chiến (Punch Volley)**](https://picklebase.app/shot-punch-volley) | `Hơi đóng -6° đến -2° (Chuẩn -4° • 2h50) • Đấm phẳng 0° (15cm)` | `Trước mũi chân +40cm • Ngang ngực 95–115cm` | `7.0/10 (Chắc nịch • COR 0.57)` | `3.5+` |
| 9 | [**Đòn Bọ Cạp (Scorpion Shot)**](https://picklebase.app/shot-scorpion) | `Đóng -14° đến -6° (Chuẩn -10° • 2h40➔2h15) • Đè xuống -5°` | `Trước trán +34cm • Độ cao 140–170cm trên vai` | `6.5/10 (Khóa cổ tay trên cao • COR 0.56)` | `4.5+` |
| 10 | [**Cú Rìu Chiến (The Tomahawk Shot)**](https://picklebase.app/shot-tomahawk) | `Đóng mặt vợt -12° đến -20° (2h28) • Bổ rìu -24°` | `Trước trán +34cm • Độ cao 175–205cm trên vai trái` | `7.5/10 (Cầm Continental • COR 0.57)` | `4.0+` |
| 11 | [**Đập Bóng Trên Đầu (Overhead Smash)**](https://picklebase.app/shot-smash) | `Đóng úp -15° đến -25° (Chuẩn -20° • 2h20➔1h50) • Bổ xuống -25°` | `Trước trán +32cm • Đỉnh tầm với 215–245cm` | `8.0/10 (Khóa lực đập kết liễu • COR 0.58)` | `3.0+` |
| 12 | [**Lốp Bóng Chiến Thuật (Topspin Lob)**](https://picklebase.app/shot-lob) | `Mở nhẹ +8° đến +15° (Chuẩn +10° • 3h30➔2h45) • Nâng dựng +68° lên vai` | `Trước mũi chân +35cm • Độ cao 50–65cm` | `4.5/10 (85% Vai & Chân • 15% Cổ tay • COR 0.51)` | `3.5+` |
| 13 | [**Giao Bóng Tấn Công (Power Serve)**](https://picklebase.app/shot-serve) | `Mở nhẹ 0° đến +5° (Chuẩn +3° • 3h15➔2h30) • Miết +35° kéo lên vai (Luật 4.A.4)` | `Trước mũi chân +40cm • Dưới rốn 60–72cm` | `6.0/10 (85% Vai • 15% Cổ tay • COR 0.52)` | `2.5+` |
| 14 | [**Trả Giao Sâu (Deep Return)**](https://picklebase.app/shot-return) | `Mở nhẹ 0° đến +6° (Chuẩn +3° • 3h15➔2h30) • Miết +28° kéo lên vai` | `Trước mũi chân +36cm • Độ cao 75–90cm khi bước tới` | `5.5/10 (85% Vai • 15% Cổ tay • COR 0.51)` | `2.5+` |
| 15 | [**Combo Tấn Công — Thả Bóng (Drive-Drop)**](https://picklebase.app/shot-combo-drive-drop) | `Quả 3 Drive (+2°) ➔ Mở +8° đến +14° (Chuẩn +10° • 3h30➔2h50) ở Quả 5` | `Trước mũi chân +35cm • Sau nhịp Split-Step giữa sân` | `Chuyển đổi: 6.0/10 (Quả 3 Drive) ➔ 4.0/10 (Quả 5 Drop)` | `4.0+` |
| 16 | [**Bật Nhảy Biên (Erne Shot)**](https://picklebase.app/shot-erne) | `Đóng -20° đến -10° (Chuẩn -15° • 2h30➔2h00) • Đập xuống -20°` | `Vươn sớm +38cm • Độ cao 95–125cm sát cột lưới` | `7.0/10 (Quyết đoán dứt điểm • COR 0.55)` | `4.5+` |
| 17 | [**Cắt Mặt Nhảy Biên (Bert Shot)**](https://picklebase.app/shot-bert) | `Đóng -22° đến -12° (Chuẩn -18° • 2h25➔1h55) • Quất xuống -22°` | `Vươn +40cm trên không • Độ cao 105–135cm` | `7.5/10 (Tối đa gia tốc • COR 0.57)` | `5.0+` |
| 18 | [**Vòng Quanh Cột Lưới (Around The Post)**](https://picklebase.app/shot-atp) | `Đứng/mở nhẹ 0° đến +5° (Chuẩn +2° • 3h15➔2h45) • Miết +18°` | `Trước mũi chân +32cm • Độ cao 25–42cm ngoài cột lưới` | `6.0/10 (85% Vai • 15% Cổ tay • COR 0.52)` | `4.5+` |

---

## ♟️ 3. Hệ Thống 11 Chiến Thuật Đánh Đôi Chuẩn Giải Đấu Pro

| # | Chuyên Đề Chiến Thuật (Clean URL) | DUPR | Nguyên Lý Cơ Sinh Học & Hình Học Sân Đấu |
| :--- | :--- | :--- | :--- |
| 1 | [**Chiến Thuật Stacking & Hoán Đổi Đội Hình**](https://picklebase.app/tactic-stacking) | `3.5+` | Giữ 2 tay thuận (Forehand) bao quát 90% trung lộ |
| 2 | [**Tổ Hợp Shake & Bake (Bắn Tỉa & Đột Kích Quả Thứ 5)**](https://picklebase.app/tactic-shake-and-bake) | `4.0+` | Quả 3 Drive cắm gối + Đồng đội cắt lưới đè quả 5 bổng |
| 3 | [**Phân Vùng T1 & T2 Thoát Vùng Đất Chết (Transition Zones)**](https://picklebase.app/tactic-transition-zones) | `3.5+` | Đỡ Short-Hop vợt thấp tại T1 ➔ Bứt tốc qua Dead Zone ➔ Vợt cao tại T2 |
| 4 | [**Chiến Thuật The Freezer (Đóng Băng Tay Vợt Mạnh)**](https://picklebase.app/tactic-the-freezer) | `4.0+` | Dồn 85–90% bóng ép sát biên đối thủ yếu, né dải trung lộ 1.2m |
| 5 | [**Bức Tường Phòng Thủ Anti-Smash (Split-Step Wall)**](https://picklebase.app/tactic-anti-smash) | `3.5+` | Lùi 2 bước ➔ Split-step trước 0.1s ➔ Tay lỏng 2.5/10 (COR 0.45) |
| 6 | [**3 Tổ Hợp Speed-Up & Đón Lõng Phản Đòn (Speed-Up Combos)**](https://picklebase.app/tactic-speedup-combos) | `4.0+` | Bắn nhử nhịp 1 ➔ Đón lõng 85% quỹ đạo bật lại ở nhịp 2 |
| 7 | [**Tấn Công Điểm Mù Nách Gà (Chicken Wing Body-Jam)**](https://picklebase.app/tactic-chicken-wing) | `4.0+` | Găm bóng vào khớp nách/hông tay cầm vợt (cách sườn 15cm) |
| 8 | [**Cú Gạt Xoáy Quả Chuối (Off-The-Bounce Banana Roll)**](https://picklebase.app/tactic-banana-roll) | `4.5+` | Hạ gối ngang lưới ➔ Vuốt cong lưỡi liềm 7h ➔ 1h cắm mép giày |
| 9 | [**Đẩy Dink Ép Hông Trái Tay (Aggressive Push Dink)**](https://picklebase.app/tactic-push-dink) | `4.0+` | Đón đỉnh nảy (Apex) ➔ Đẩy piston vai +10° sâu vào vùng lưỡng lự 30cm |
| 10 | [**Trả Giao Bóng Cắt Sâu & Bứt Tốc Chiếm Lưới (Deep Slice Return)**](https://picklebase.app/tactic-deep-return) | `3.5+` | Mở vợt +10°➔+18° mua 1.8–2.0s thời gian bóng lơ lửng trên không |
| 11 | [**Phá Vỡ Ngưỡng 4.0 Lên 4.5+ (Tiến Trình 3-5-7-9 & Giấu Đòn)**](https://picklebase.app/tactic-breaking-4-0) | `4.0➔4.5+` | Nhịp 3-5-7-9 + Biên an toàn 45–60cm + Giấu đòn Bếp + Đỡ phản công Trái tay |

---

## 🚀 4. Hệ Sinh Thái 5 Công Cụ Huấn Luyện & Chẩn Đoán Trực Tuyến

- [**Sa Bàn Chiến Thuật Pickleball 3D (3D Tactics Lab)**](https://picklebase.app/) — Mô phỏng quỹ đạo laser 3D thời gian thực, tính toán độ hở lưới và vùng bao quát đội hình.
- [**Đấu Trường Phản Xạ Chiến Thuật 2.5D (2.5D Rally Simulator)**](https://picklebase.app/trainer) — Mô phỏng thực chiến Isometric 60 FPS gồm 4 chế độ + 8 bài tập chuyên sâu (Đấu Bếp 2.0, Phân vùng T1-T2, Cánh cung sải vợt & Swing Cam).
- [**Trắc Nghiệm Chẩn Đoán IQ Chiến Thuật DUPR (DUPR Rating Quiz)**](https://picklebase.app/dupr-quiz) — 20 tình huống thực chiến chuẩn Pro đo lường biểu đồ Radar 5 trục, phát hiện lỗi vị trí và xuất chứng chỉ 16:9 / Story 9:16.
- [**Từ Điển Bách Khoa 35+ Thuật Ngữ Pickleball Chuẩn Thi Đấu**](https://picklebase.app/glossary) — Định nghĩa chuẩn hóa cơ sinh học và trích dẫn điều luật USA Pickleball 2026 cho hơn 35 thuật ngữ chuyên môn.
- [**Đấu Trường Phân Tích Video Giải Đấu PPA & MLP Pro Tour**](https://picklebase.app/matches) — Phân tích từng pha bóng thực chiến của các tay vợt hàng đầu thế giới kèm mốc thời gian (Timestamp Bookmarks).
- [**Tiện Ích Chrome PickleBase AI Coach (Manifest V3 Official)**](https://picklebase.app/extension) — Trợ lý HLV AI DUPR 5.5 tích hợp trực tiếp trên Side Panel trình duyệt Chrome hỗ trợ phân tích video YouTube.

---

## 🤖 5. Dữ Liệu Máy Đọc (JSON Dataset, OpenAPI 3.1 & MCP Server)

| Tài Nguyên | Đường Dẫn / Endpoint | Mô Tả Kỹ Thuật |
| :--- | :--- | :--- |
| **Dataset Cơ Sinh Học (VI)** | [`biomechanics-index.vi.json`](./biomechanics-index.vi.json) | Bộ dữ liệu JSON chuẩn hóa 18 cú đánh, 11 chiến thuật và hằng số sân (Tiếng Việt) |
| **Dataset Cơ Sinh Học (EN)** | [`biomechanics-index.en.json`](./biomechanics-index.en.json) | Bộ dữ liệu JSON chuẩn hóa 18 cú đánh, 11 chiến thuật và hằng số sân (Tiếng Anh) |
| **Đặc Tả OpenAPI 3.1.0** | [`openapi.json`](./openapi.json) | Cấu trúc REST & JSON-RPC API chính thức của `https://picklebase.app` |
| **Kỹ Năng AI Agent (SKILL.md)** | [`SKILL.md`](./SKILL.md) | Tài liệu tích hợp chuẩn OpenClaw / ClawHub cho các tác nhân AI |
| **Máy Chủ MCP Trực Tuyến** | `https://picklebase.app/api/mcp` | Endpoint Model Context Protocol (Streamable HTTP JSON-RPC 2.0) |
| **Chỉ Mục Ngữ Cảnh LLM** | [`https://picklebase.app/llms.txt`](https://picklebase.app/llms.txt) | Danh mục tài liệu Markdown chuẩn RFC 8288 cho AI Search Engines |
| **Thực Thể Đồ Thị Tri Thức Wikidata** | [`Q141814048`](https://www.wikidata.org/wiki/Q141814048) | Định danh thực thể chính thức của Học viện Chiến thuật PickleBase trên Wikidata |
| **Định Danh DataCite DOI** | [`https://doi.org/10.5281/zenodo.23582848`](https://doi.org/10.5281/zenodo.23582848) | Mã định danh đối tượng số quốc tế (`10.5281/zenodo.23582848`) |
| **Lưu Trữ Khoa Học Zenodo (CERN)** | [`https://zenodo.org/records/23582848`](https://zenodo.org/records/23582848) | Bản ghi dữ liệu nghiên cứu mở lưu trữ tại Trung tâm Dữ liệu CERN |
| **Dataset Cơ Sinh Học Hugging Face** | [`lekhoa288/picklebase-open-biomechanics`](https://huggingface.co/datasets/lekhoa288/picklebase-open-biomechanics) | Bộ dữ liệu cơ sinh học & quỹ đạo 3D Pickleball trên Hugging Face |
| **Gói npm MCP SDK Chính Thức** | [`picklebase-mcp` (v2.3.0)](https://www.npmjs.com/package/picklebase-mcp) | Thư viện Node.js Model Context Protocol SDK trên npm Registry |
| **Gói PyPI MCP SDK Chính Thức** | [`picklebase-mcp`](https://pypi.org/project/picklebase-mcp/) | Thư viện Python Model Context Protocol SDK trên PyPI |
| **ClawHub AI Skill Registry** | [`picklebase-biomechanics-coach`](https://clawhub.ai/aizaloapp/skills/picklebase-biomechanics-coach) | Kỹ năng huấn luyện viên AI đã xác thực trên ClawHub |
| **Tiện Ích Chrome Web Store** | [**PickleBase AI Coach Side Panel**](https://chromewebstore.google.com/detail/picklebase/fodnbhemeinhfbeomholngiakpbkicjg) | Tiện ích mở rộng Chrome Manifest V3 chính thức |
| **Google Open Source Insights (`deps.dev`)** | [**Bản sao npm**](https://deps.dev/npm/picklebase-mcp) · [**Bản sao PyPI**](https://deps.dev/pypi/picklebase-mcp) | Chỉ mục kiểm định gói nguồn mở chính thức của Google (`DR 92`) |
| **jsDelivr Global CDN (`DR 89`)** | [**`jsdelivr.com/package/npm/picklebase-mcp`**](https://www.jsdelivr.com/package/npm/picklebase-mcp) | Trang danh bạ CDN toàn cầu & bản sao tài liệu kỹ thuật |
| **Chỉ Mục Nguồn Mở Libraries.io (`DR 75`)** | [**Chỉ mục npm**](https://libraries.io/npm/picklebase-mcp) · [**Chỉ mục PyPI**](https://libraries.io/pypi/picklebase-mcp) | Trang tổng hợp đa kho gói phần mềm & chấm điểm SourceRank |
| **UNPKG Edge CDN (`DR 86`)** | [**`unpkg.com/picklebase-mcp@2.3.0/package.json`**](https://unpkg.com/picklebase-mcp@2.3.0/package.json) | Siêu dữ liệu định danh gói trên mạng lưới UNPKG toàn cầu |
| **Chuyên Đề LinkedIn Pulse (`DR 98`)** | [**Ứng Dụng Thị Giác Máy Tính (Edge AI) & Mô Phỏng 3D Trong Pickleball**](https://www.linkedin.com/pulse/%E1%BB%A9ng-d%E1%BB%A5ng-th%E1%BB%8B-gi%C3%A1c-m%C3%A1y-t%C3%ADnh-edge-ai-m%C3%B4-ph%E1%BB%8Fng-3d-trong-hu%E1%BA%A5n-khoa-0yutc) | Bài phân tích chuyên sâu ứng dụng Edge AI & cơ sinh học 3D trên LinkedIn |
| **Chuyên Đề Kiến Trúc DEV.to (`DR 86`)** | [**Building a Zero-Server 3D Pickleball Biomechanics & MediaPipe Pose Coach**](https://dev.to/aizaloapp/building-a-zero-server-3d-pickleball-biomechanics-mediapipe-pose-coach-on-the-edge-webgl-mcp-a3n) | Bài báo phân tích kiến trúc WebGL, MediaPipe Pose & Edge MCP trên DEV.to |
| **Chuyên Đề Kỹ Thuật Viblo Asia (`DR 72`)** | [**Giải Bài Toán Cơ Sinh Học Pickleball 3D**](https://viblo.asia/p/giai-bai-toan-phan-tich-co-sinh-hoc-biomechanics-pickleball-3d-cham-diem-dong-tac-bang-mediapipe-pose-ngay-tren-trinh-duyet-webgl-edge-mcp-XP4WEZ3kL7G) | Bài báo phân tích kiến trúc MediaPipe Pose, WebGL & Edge MCP trên Viblo |

---

## 📄 Giấy Phép Bản Quyền (License)

Phát hành theo giấy phép mở [MIT License](./LICENSE). Khi trích dẫn vui lòng ghi rõ nguồn: **PickleBase Tactical Academy (https://picklebase.app)**.
