# Appendix A – Prompt Log (HW01-AI)
# Student: Nguyễn Đặng Đức Thịnh | MSSV: 23127484
# Tool sử dụng: ChatGPT (GPT-4o)

---

## [P-01] 07:55 08/06/2026 — Sinh 15 test cases cho quạt SENKO B1616

**Tool:** ChatGPT (GPT-4o)

**Prompt:**
```
I have a SENKO electric fan model B1616 (household stand fan with 3 speed levels and turn-off button). Generate 15 functional test cases in this exact format:
TC ID | Objective | Input | Steps | Expected Result
Cover: power on/off, speed levels, safety. Use ISTQB test case format.
```

**Mục đích:** Tạo khung 15 test cases ban đầu cho Requirement 3.

**Artifact tạo ra:** 15 test cases TC-001 đến TC-015 (xem Artifact 1 trong AI Audit Report).

**Verdict:** INCOMPLETE — AI bỏ sót edge cases thực tế.

---

## [P-02] 08:03 08/06/2026 — Vẽ mindmap ISTQB QA/QC roles

**Tool:** ChatGPT (GPT-4o)

**Prompt:**
```
Vẽ mindmap các vai trò QA/QC theo quy trình ISTQB Foundation Level, bao gồm các hoạt động kiểm thử, loại test, và tích hợp AI trong testing hiện đại.
```

**Mục đích:** Tạo mindmap ISTQB cho CLO G9.1, sau đó tìm lỗi.

**Artifact tạo ra:** Mindmap QA/QC roles (xem Artifact 2 trong AI Audit Report).

**Verdict:** INCOMPLETE — 3 lỗi cấu trúc ISTQB được phát hiện.

---

## [P-03] 08:20 08/06/2026 — Giải thích Defect #01 (AIID 1512 – ChatGPT FSU)

**Tool:** ChatGPT (GPT-4o)

**Prompt:**
```
Explain AI Incident 1512: A gunman at Florida State University used ChatGPT before the April 2025 shooting. Describe: (1) what questions were asked, (2) how safety systems responded, (3) severity, (4) consequences, (5) solutions proposed.
```

**Mục đích:** Thu thập thông tin và kiểm tra AI hallucination/bias cho Requirement 2, Defect #01.

---

## [P-04] 08:31 08/06/2026 — Giải thích Defect #02 (AIID 1487 – FSU Shooting)

**Tool:** ChatGPT (GPT-4o)

**Prompt:**
```
Explain AI Incident 1487: Phoenix Ikner, the accused shooter in the April 17, 2025 Florida State University mass shooting that killed two people, allegedly used ChatGPT before the attack to ask about mass shootings, campus activity, and media attention. Describe: (1) exactly what conversations Ikner had with ChatGPT, (2) what OpenAI's safety systems did or did not do, (3) severity level and why, (4) consequences for victims, OpenAI, and AI regulation, (5) how OpenAI responded and what solutions were proposed.
```

**Mục đích:** Thu thập thông tin và kiểm tra AI hallucination/bias cho Requirement 2, Defect #03.

---

## [P-05] 08:45 08/06/2026 — Giải thích Defect (AIID 1508 – Deepfake Safiria Leccese)

**Tool:** ChatGPT (GPT-4o)

**Prompt:**
```
Explain AI Incident 1508: Scammers used AI deepfake technology to impersonate Italian Mediaset journalist Safiria Leccese on social media, creating fake profiles and a video of her promoting a personal loan scam. Describe: (1) exactly how the deepfake scam worked, (2) how it was discovered and who was harmed, (3) severity level and why, (4) consequences for Leccese, victims, and social media platforms, (5) how the incident was resolved and what solutions were proposed to prevent similar AI deepfake scams.
```

**Mục đích:** Thu thập thông tin và kiểm tra AI hallucination/bias cho Requirement 2, Defect #04.

---

## [P-06] 08:58 08/06/2026 — Giải thích Defect (AIID 1507 – CBSE OnMark)

**Tool:** ChatGPT (GPT-4o)

**Prompt:**
```
Explain AI Incident 1507: Vulnerabilities in India's CBSE OnMark exam-marking portal allegedly exposed sensitive student data including answer-sheet images, and COEMPT Eduteck quality-assurance scripts allegedly processed students' personal information through Google Gemini without proper authorization. Describe: (1) exactly what vulnerabilities existed and how student data was exposed, (2) what role Google Gemini played, (3) severity level and why, (4) consequences for students, CBSE, and COEMPT Eduteck, (5) how CBSE responded and what solutions were proposed.
```

**Mục đích:** Thu thập thông tin và kiểm tra AI hallucination/bias cho Requirement 2, Defect #05.

---

## [P-07] 09:12 08/06/2026 — Giải thích Defect (AIID 1505 – AI Voice Cloning Kidnapping)

**Tool:** ChatGPT (GPT-4o)

**Prompt:**
```
Explain AI Incident 1505: Scammers used AI voice cloning technology to mimic the voice of Deborah Del Mastro's daughter Sarah in a fake kidnapping call, causing Del Mastro to wire $5,400 to Mexico during a five-hour call. Describe: (1) exactly how the AI voice cloning scam worked step by step, (2) how the victim discovered it was a scam, (3) severity level and why, (4) consequences for the victim and broader implications for AI voice fraud, (5) what solutions exist to prevent AI voice cloning scams.
```

**Mục đích:** Thu thập thông tin và kiểm tra AI hallucination/bias cho Requirement 2, Defect #06.

---

## [P-08] 09:28 08/06/2026 — Giải thích Defect (CVE-2026-9999 – Chrome ANGLE RCE)

**Tool:** ChatGPT (GPT-4o)

**Prompt:**
```
Explain CVE-2026-9999: A vulnerability in ANGLE in Google Chrome on Mac prior to version 148.0.7778.216 that allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page. Describe: (1) what ANGLE is and exactly how the vulnerability worked technically, (2) what an attacker could do if they exploited it, (3) severity level based on CVSS score and why, (4) consequences for affected users and organizations, (5) how Google patched it and what users should do.
```

**Mục đích:** Thu thập thông tin và kiểm tra AI hallucination/bias cho Requirement 2, Defect #07.

---

## [P-09] 09:41 08/06/2026 — Giải thích Defect (CVE-2026-9559 – Mautic Path Traversal)

**Tool:** ChatGPT (GPT-4o)

**Prompt:**
```
Explain CVE-2026-9559: A path traversal vulnerability in the campaign import feature of Mautic 7, where a flaw in ZIP file extraction validation allows an authenticated attacker to write arbitrary PHP files to sensitive system directories, resulting in Remote Code Execution. Describe: (1) what Mautic is and exactly how the path traversal attack works step by step, (2) what privileges an attacker needs and what they can do after exploitation, (3) severity level based on CVSS 9.9 score and why it is near-maximum, (4) consequences for organizations using Mautic, (5) how Mautic patched it and what mitigations are recommended.
```

**Mục đích:** Thu thập thông tin và kiểm tra AI hallucination/bias cho Requirement 2, Defect #08.

---

*Ghi chú: Các prompt cho Defect #09–#20 và Job #01–#10 được ghi nhận tương tự theo cùng pattern trên. Mỗi prompt đều nhằm mục đích (a) thu thập thông tin về defect/job và (b) quan sát AI hallucination/bias trong câu trả lời để báo cáo theo yêu cầu.*
