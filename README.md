# CloudForge Architecture Assistant (MVP)

Internal AI Assistant สำหรับช่วยออกแบบ Cloud Architecture เบื้องต้น  
รองรับ AWS • Azure • Google Cloud

## คุณสมบัติ (MVP)

- รับ Requirement จากผู้ใช้
- ออกแบบ High-level Architecture
- แนะนำบริการ Cloud ที่เหมาะสม
- สร้าง ADR (Architecture Decision Record) ร่าง
- สร้าง Mermaid Diagram

## วิธีรันด้วย Google Colab (แนะนำ)

1. เปิดไฟล์ `notebooks/CloudForge_Architecture_Assistant.ipynb` ด้วย Google Colab
2. ใส่ API Key (แนะนำใช้ Colab Secrets)
3. รันเซลล์ทั้งหมด
4. ระบบจะสร้างลิงก์ชั่วคราวให้ใช้งานได้ทันที

## โครงสร้างโปรเจกต์

```text
├── prompts/
│   └── system_prompt.txt          # Prompt หลักของระบบ
├── notebooks/
│   └── CloudForge_Architecture_Assistant.ipynb
├── data/
│   └── samples/                   # เอกสารตัวอย่าง (อนาคต)
├── requirements.txt
└── README.md
