# Feature: <ประตูสแกนใบหน้า>
Spec ID: SPEC-<PREFIX>-001 | Source: SRS v<x.y> ข้อ <3.1 ...> | Use case: UC-<xx>
Owner: <ทีม/คน> | Status: Draft v1 | Updated: <YYYY-MM-DD>
Depends on: - | Reviewed by: -

## Goal
<ใครได้อะไร 1-3 ประโยค ในมุมผลลัพธ์ของผู้ใช้ ไม่ใช่รายการฟีเจอร์ ใส่ตัวเลขจาก NFR ด้านการใช้งานได้ถ้ามี>

## Scope
### In scope
- <หัวข้อที่ฟีเจอร์นี้ครอบคลุม>
### Out of scope
- <use case ข้างเคียงที่ไม่ทำ อ้าง UC-xx หรือชื่อ spec>
- <use case ที่ถูก include ให้เขียนว่า "ถือว่าทำแล้ว (precondition)">

## Constraints
- <DOM-xxx> <ข้อบังคับจากกฎหมาย/ระเบียบ ที่โค้ดตรวจได้>
- <IF-xxx> <ระบบภายนอกที่ฟีเจอร์นี้แตะ ทิศทางข้อมูล และทำอย่างไรเมื่อมันไม่ตอบ>
- <CON-xxx> <เทคโนโลยีหรือมาตรฐานที่บังคับ>

## Requirements
- <FR-xxx-01> <ระบบต้องทำอะไร 1 เรื่องต่อ 1 ข้อ ไม่มี "และ" เชื่อม 2 พฤติกรรม>
- <FR-xxx-02> <จาก alternative flow ระบุที่มา เช่น (UC-xx 3a)>
- <FR-xxx-03> <จาก exception flow ระบุที่มา เช่น (UC-xx 5b)>

## Quality Requirements
- <NFR-xxx-01> <คุณลักษณะ> + <เงื่อนไข> + <ตัวชี้วัดและค่าเป้าหมาย> (ต้องมีตัวเลข ไม่มีตัวเลขให้ย้ายไป Open Questions)

## Acceptance Criteria
- [ ] AC-<PREFIX>-01 (<FR ที่พิสูจน์>)
      Given <สถานะที่เตรียมได้>
      When  <การกระทำเดียว>
      Then  <ค่าที่สังเกตได้จากภายนอก>
- [ ] AC-<PREFIX>-02 (<FR/NFR ที่พิสูจน์>)
      Given <...>
      When  <...>
      Then  <...>

## Assumptions and Open Questions
- ASM-01 <สิ่งที่ทีมตัดสินใจไปก่อนเพื่อเดินหน้า>
- Q-01 <คำถามที่ยังตอบไม่ได้> -> ต้องถาม <ใคร>
- Q-02 <...> -> ต้องถาม <ใคร>

## Changelog
- v1 <YYYY-MM-DD> ร่างแรกจาก SRS v<x.y>
