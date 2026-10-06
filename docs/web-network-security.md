# Web & Network Security

## Nền tảng học (nguồn kinh điển)

- **[PortSwigger Web Security Academy](https://portswigger.net/web-security)** —
  Miễn phí, tốt nhất thế giới cho web application security, có lab thực hành
  (XSS, SQLi, SSRF, request smuggling, auth bypass...).
- **[OWASP Top 10](https://owasp.org/www-project-top-ten/)** — 10 rủi ro bảo mật
  web phổ biến nhất, chuẩn tham chiếu ngành.
- **[OWASP Web Security Testing Guide (WSTG)](https://owasp.org/www-project-web-security-testing-guide/)** —
  Phương pháp luận kiểm thử web đầy đủ nhất.
- **[OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)** — Cheatsheet
  chống/khai thác từng loại lỗ hổng.
- **[TryHackMe](https://tryhackme.com/)** — Tốt nhất cho người mới, có "room"
  hướng dẫn từng bước, AttackBox trong browser.
- **[HackTheBox](https://www.hackthebox.com/)** — Trung cấp/cao cấp, Academy +
  machine thực tế mô phỏng doanh nghiệp.

## Cheatsheet & Payload (cập nhật liên tục)

- **[PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)** —
  Payload cho mọi loại tấn công web (cập nhật ~hàng tuần).
- **[HackTricks](https://book.hacktricks.xyz/)** — "Thánh kinh" cheatsheet pentest,
  từ network đến web, cloud, AD.
- **[GTFOBins](https://gtfobins.github.io/)** — Binary Unix có thể bị lợi dụng để
  bypass restriction (privilege escalation).
- **[LOLBAS](https://lolbas-project.github.io/)** — Tương tự GTFOBins nhưng cho Windows.
- **[revshells.com](https://www.revshells.com/)** — Tạo reverse shell payload nhanh.

## Công cụ chính

- **Burp Suite** (Community/Pro) — Proxy intercept/sửa request, công cụ web pentest #1.
- **Nmap** — Network scanning/enumeration.
- **Wireshark** — Phân tích traffic mạng.
- **CyberChef** — "Dao Thụy Sĩ" cho encode/decode/crypto/data analysis
  ([gchq.github.io/CyberChef](https://gchq.github.io/CyberChef/)).
- **Nuclei** (ProjectDiscovery) — Scan lỗ hổng tự động theo template, cập nhật rất nhanh.
- **Shodan / Censys** — Search engine cho thiết bị/service lộ trên Internet (OSINT mạng).

## Mảng mới / xu hướng 2025–2026

- **Agentic AI & browser security**: Trail of Bits (1/2026) công bố tấn công khai
  thác lỗ hổng isolation trong "agentic browser" (AI tự duyệt web) — xem
  [blog.trailofbits.com](https://blog.trailofbits.com/).
- **AI-assisted vulnerability research**: VulnCheck ghi nhận >14.000 exploit cho
  >10.000 CVE riêng trong 2025, tăng 16.5% YoY, một phần do PoC sinh bởi AI.
- **Strix** — Công cụ pentest tự động dùng AI agent, cập nhật tích cực (10/2026).
- **SpiderFoot** — OSINT automation cho threat intel/attack surface, vẫn cập nhật tích cực.

## Ghi chú sử dụng

Chỉ chạy scan/khai thác trên hệ thống bạn sở hữu hoặc có ủy quyền bằng văn bản
(phạm vi bug bounty, hợp đồng pentest). Nmap/Nuclei/Burp quét vào hệ thống không
được phép có thể vi phạm pháp luật.
