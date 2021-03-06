---
title: "[รีวิว] TechJam 2018 Regional Competition — Code Squad ภาคเหนือ"
tags:
  - Review
  - Programming
  - Algorithms and Data Structures
date: 2018-09-27 16:00:00 +0700
comment: origin
origin:
  - name: "Medium"
    url: "https://medium.com/@aquablitz11/รีวิว-techjam-2018-regional-competition-code-squad-ภาคเหนือ-3c180a101890"
---

เอาตรง ๆ คืองานนี้มาแข่งเพื่อล่ารางวัลครับ :3 แต่ก็ไม่ได้คาดหวังอะไรมาก เพราะนี่ไม่ใช่แค่การแข่งขันในระดับ ม.ปลาย เท่านั้น นักศึกษามหาวิทยาลัย หรือแม้กระทั่งอาจารย์และ software developer คนอื่น ๆ ก็สามารถลงแข่งได้ด้วย

แต่ได้ยินมาว่างานนี้เน้น Algorithms และ Data Structures ผมก็เลยคิดว่า สกิลที่สะสมมาตั้งแต่งานแข่ง OI ต่าง ๆ (TOI, APIO, IOI) กับ Google Code Jam หรือพวกเว็บ Codeforces, CSAcademy อะไรงี้น่าจะช่วยได้บ้างแหละ ผนวกกับช่วงเวลาที่แข่ง ผมไม่ได้ติดงานอย่างอื่นพอดี ก็เลยลองลงแข่งรอบ audition เล่น ๆ แล้วก็พบว่า

โจทย์ง่ายมาก ทำ 1 ชม. เสร็จ ติดรอบระดับภาคชิลๆ :D

{: .figure}
> <iframe width="560" height="315" src="https://www.youtube.com/embed/2kNSMbaJFz4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
> คลิป Teaser ของ Techjam 2018 — Regional Competition ภาคเหนือ

## First Impression

แค่เดินเข้าพื้นที่จัดงานไปก็รู้แล้วว่า KBTG ไม่ได้จัดงานนี้เล่น ๆ องค์ประกอบแต่ละอย่างจัดตกแต่งสวยงามเวอร์วังอลังการงานสร้าง สิ่งที่ผมต้องทำเมื่อเข้างานไปก็คือเดินไปโต๊ะลงทะเบียนละก็กรอกข้อมูลต่าง ๆ นานา จัดการไปตามระเบียบพิธีการยาว ๆ ไป

หลังลงทะเบียนเสร็จแล้วทีมงานก็จะแจกไอเทมสุดพื้นฐาน 3 อย่าง นั่นก็คือ
- สติ๊กเกอร์ Squad กับหมายเลขทีมที่เอามาแปะตรงหน้า T-Shirt สวย ๆ ที่อุตส่าห์ใส่ไป กลัวคนอื่นจะไม่รู้ว่าอยู่ Squad ไหน
- สายรัดข้อมือ Code Squad ที่ติดกาวเหนียวเวอร์ ๆ
- กล่องขนมที่ประกอบไปด้วยขนมปังและน้ำผลไม้ในตำนาน

![](https://cdn-images-1.medium.com/max/400/1*uBJUqK-XE96Bk9PbwoB3ow.jpeg)
{: .float-left}
ส่วนอย่างสุดท้ายที่เรียกได้ว่าเป็นแรร์ไอเทมในงานนี้ก็คงไม่พ้นกระติกน้ำขนาดใหญ่ที่เขียนคำว่า Tomorrow Squad ติดไว้อย่างเท่ ซึ่งเอาออกไปใช้อวดคนอื่นนอกงานได้ด้วย อันนี้ของดีมากครับ ขอขอบคุณทาง KBTG ที่อุตส่าห์ลงทุนขนาดนี้ \_/\\\_

นอกจากนี้ในงานจะมีโต๊ะที่มีขนมเต็มไปหมด รวมถึงพวกเครื่องดื่ม น้ำอัดลม มีให้ไม่อั้น ระหว่างแข่งไม่ต้องห่วงเลยว่าของกินจะไม่พอ

{: .clear-float}
หลังจากแนะนำสถานที่เสร็จสรรพแล้ว สิ่งที่ต้องทำต่อไปนั่นก็คือ… รอ! พอดีมาเช้าเกินไปเลยต้องนั่งรอไป 2 ชม. ยาว ๆ ไป D:

## New Challengers Appeared!
จะให้รออยู่เฉย ๆ มันก็น่าเบื่อ ผมจึงถือโอกาสไปเดินทัวร์ในงานเล่น ๆ แล้วก็พบกับคนที่ไม่คิดว่าจะมาโผล่ในภาคเหนือ นั่นก็คือเพื่อนที่เพิ่งไปแข่ง IOI 2018 มาด้วยกันแล้วได้เหรียญเงิน O_O"

ยังไม่พอ เขามาพร้อมกับผู้แทน IOI 2016 ที่ได้เหรียญทองแดงอีกคนนึง รวมกันเป็น **Team ↓↓↓ Second Place ↓↓↓** ตอนนี้คิดอะไรไม่ออกนอกจากอุทาน เยดเข้ ในใจละครับ ลาก่อนเงิน 30,000 บาท ลาก่อนรูปชนะเลิศแบบ solo ขึ้นเพจเท่ ๆ T_T

แต่นอกเหนือจากทีมผู้แทนแล้ว ก็ยังได้พบกับอีกทีมนึงที่ผมรู้จักดี นั่นก็คือ **Team PlugFire** ของท่านพี่ ChimengSoso กับเพื่อนพี่เขาอีกคนหนึ่ง ซึ่งทั้งคู่ก็เป็นเทพจาก CompSci มช. นั่นเอง

เห็นว่าช่วงนี้พี่แกกำลังทำแชนแนลสอนเขียนโปรแกรมใน YouTube อยู่ ว่าง ๆ ก็**[เข้าไปส่องและก็ subscribe](https://www.youtube.com/channel/UC9GH5OL2YrdtI--py1hDoaQ)** กันหน่อยละกันนะครับ #ยังไม่ได้ค่าsponsor

## Setting the Rules of the Game

หลังจากพบปะกับแต่ละทีมเสร็จแล้ว ก็ถึงเวลาอันสมควรที่ทีมงานจะเรียกเข้าห้องแข่งขันพอดีเลย เมื่อเดินเข้าไปในห้อง สิ่งที่อยู่ตรงหน้าก็คือโพเดียม 10 ตัวสำหรับผู้เข้าแข่งขันกับจอใหญ่ ๆ ตรงกลาง 1 จอ O_O นี่ไม่ใช่การแข่งขันเขียนโปรแกรมธรรมดา ๆ แล้วครับ มันคือ Game Show ดี ๆ นี่เอง

กรรมการอธิบายว่า การแข่งขันจะแบ่งออกเป็นสามรอบ คือ

1. **Quickfire** — รอบคิดเร็ว มีโจทย์มาให้ต้องตอบได้ภายในเวลาที่กำหนด (ประมาณ 20 นาที) โจทย์ทั้งหมด 5 ข้อ ข้อละ 4 คะแนน รวมเป็น 20 คะแนน

2. **Ponder** — รอบคิดวิเคราะห์ซึ่งจะคล้าย ๆ กับ Quickfire แต่จะมีเวลาให้มากถึง 5 นาที และก็สามารถใช้คอมพิวเตอร์ช่วยแก้โจทย์ได้ ทีมที่เสร็จเป็นทีมแรกจะได้ 7 คะแนน ทีมต่อ ๆ ไปก็ลดลงมาเหลือ 6, 5, 4, … มีโจทย์ 5 ข้อเช่นกัน ดังนั้นคะแนนมากที่สุดที่เป็นไปได้คือ 35 คะแนน

3. **Coding** — รอบเขียนโปรแกรมที่แท้จริง มีโจทย์มาให้สามข้อ ให้เขียนโปรแกรมที่รันผ่าน Test Case ต่าง ๆ ที่กำหนดไว้แต่ละข้อมีคะแนนให้ 15 คะแนน ดังนั้นคะแนนรวมมากสุดคือ 45 คะแนน

หลังจากแข่งเสร็จทั้งสามรอบแล้ว จะเอาคะแนนแต่ละรอบมารวมกันแล้วจัดอันดับ ถ้าคะแนนเท่ากันจะจัดอันดับตามเวลาที่ใช้ในรอบ Coding ซึ่งกรรมการยังไม่อธิบาย ณ ตอนนี้

เนื่องจากมีทีมเข้าแข่งขันทั้งหมด 20 ทีม ทำให้จัดแข่งขัน 2 รอบแรกพร้อมกันทั้งหมดไม่ได้ เลยต้องแบ่งออกเป็นสองกลุ่ม กลุ่มละ 10 ทีมก่อน ซึ่งแน่นอนว่าคงไม่มีวิธีอะไรที่ดีไปกว่าการสุ่มด้วย Pseudorandom Number Generator อย่างการสับไพ่ในมือนี่แหละ

ผลออกมาพบว่า **Team ↓↓↓ Second Place ↓↓↓** ได้แข่งก่อนใน group แรก ส่วนทีมของผม (**Team AquaBlitz11**) กับ **Team PlugFire** แข่งใน group ที่สอง เพราะฉะนั้นก็ต้องนั่งรอกันไปอีกยาว ๆ

## Let the Game Begin!

หลังจากผ่านไปอีกประมาณ 1 ชม. ครึ่ง ในที่สุด group แรกก็แข่งขันเสร็จสิ้น พวกผมจึงถูกเรียกเข้าไปในสมรภูมิรบ แล้วกรรมการจึง assign ตำแหน่งโพเดียมให้แต่ละทีมด้วยการสับไพ่อีกเช่นเคย

นับเป็นเรื่องน่าบังเอิญที่ทีมผมกับทีมพี่ชิเหม่งดันได้อยู่โพเดียมใกล้กันอีก O_O"

และแล้วการแข่งขันรอบแรกก็เริ่มต้นขึ้น…

### Round 1 — Quickfire

ในการแข่งขันรอบ Quickfire กรรมการจะนำโจทย์ขึ้นบนจอขนาดใหญ่ที่อยู่ตรงกลางห้อง แล้วอ่านโจทย์ให้ฟัง หลังจากอ่านโจทย์เสร็จแล้ว จะให้เวลาทำโจทย์โดยโจทย์แต่ละข้อตั้งแต่ 5 วินาทีถึง 60 วินาที ขึ้นอยู่กับความยาก (แต่ในงานแข่งจริง ๆ เหมือนจะ 20–30 วินาทีทุกข้อ)

จุดที่สำคัญคือ ไม่สามารถใช้คอมพิวเตอร์ระหว่างทำโจทย์ได้ ใช้ได้เพียงแค่ whiteboard และปากกาที่เตรียมให้เท่านั้น แล้วเมื่อหมดเวลาแล้วแต่ละทีมจะต้องตั้ง whiteboard โชว์คำตอบที่ตัวเองได้ทันที

สองข้อแรกถือว่าอยู่ในระดับค่อนข้างง่าย เลยไม่มีปัญหาอะไร แต่ข้อที่ 3 กับข้อที่ 4 ผมพลาดหนักมากก็เลยทำให้เสียคะแนนสองข้อนี้ไป ส่วนข้อที่ 5 ที่ดูแทบจะเป็นไปไม่ได้ที่จะคิดในเวลา 20 วินาที ผมเดาคำตอบเอา แล้วก็ดันถูกพอดี O_O"

สรุป ตอนนี้มีคะแนนเก็บไว้แล้ว 12 คะแนนจากทั้งหมด 20 คะแนน

### Round 2 — Ponder

![](https://cdn-images-1.medium.com/max/300/1*FssgSoJg3WHntHE7rCxzag.jpeg)
{: .float-left}
รอบนี้จะมีเวลาให้ทำโจทย์มากขึ้น และสามารถใช้คอมพิวเตอร์ได้ แต่ว่าคะแนนจะขึ้นอยู่กับลำดับการทำโจทย์

ทีมที่ทำโจทย์เสร็จก่อน จะต้องรีบวิ่งมาหยิบธงตามลำดับตรงกลางห้อง แล้วกรรมการจะตรวจให้คะแนน โดยทีมแรกที่ถูกต้องจะได้ 7 คะแนน ทีมถัดมาได้ 6, 5, 4, 3, … ลงมาเรื่อย ๆ

{: .clear-float}
สำหรับรอบนี้ เนื่องจากมีเวลาให้ 5 นาทีผมเลยรู้สึกอุ่นใจอยู่พอสมควร ผมเลือกเขียนโปรแกรมภาษา C++ ทั้ง 5 ข้อเพราะเป็นภาษาที่ผมคุ้นเคยที่สุด แต่เพื่อไม่ให้เสียเปรียบคนที่ใช้ภาษา Python ผมจึงได้เตรียม template code เอาไว้ประมาณร้อยกว่าบรรทัด เพื่อจะได้พิมพ์อะไรหลาย ๆ อย่างได้สั้นพอ ๆ กับภาษา Python จะได้ไม่เสียเวลา

ถึงอย่างไรก็ตาม เนื่องจากว่าผมแข่งแบบ solo จึงเสียเวลากับการตรวจโค้ดนานอยู่พอสมควร (กลัวบัค) เลยทำบางข้อได้ช้ากว่าคนอื่น สำหรับรอบนี้ ผมทำได้ไวสุด 3 ข้อ ส่วนอีก 2 ข้อได้อันดับ 2 เลยได้คะแนนแค่ 33 คะแนนจาก 35 คะแนน

หลังจากการแข่งขันสองรอบแรกเสร็จแล้ว กรรมการจึงปล่อยให้ผู้เข้าแข่งขันออกมาทานข้าวเที่ยงก่อน ส่วนช่วงบ่ายก็จะเป็นการแข่งขันในรอบ Coding ที่หลาย ๆ คนรอคอยนั่นเอง

แน่นอนว่าทันทีที่ผมออกมาจากห้อง ผมก็รีบตรงเข้าไปหา **Team ↓↓↓ Second Place ↓↓↓** เพื่อถามคะแนน พบว่าทีมนั้นทำโจทย์รอบ Quickfire ได้ 4 ข้อ (ผมได้ 3 ข้อ) ส่วนรอบ Ponder ได้ 7 คะแนนทุกข้อ

วิธีเดียวที่ผมจะชนะทีมนี้คือต้องเอาชนะรอบ Coding ให้ได้ แต่จากที่สันนิษฐานไว้ว่าโจทย์รอบ Coding จะมีระดับความยากไม่เกินโจทย์ TOI คิดว่าคงเป็นไปไม่ได้ เพราะน่าจะได้คะแนน (เต็ม) เท่ากัน มันจบแล้วล่ะ ฮือออ T_T

{: .figure}
> ![](https://cdn-images-1.medium.com/max/3096/1*G5Fy6WVgYPSM5jFyZRYJ4Q.jpeg)
>
> กินข้าวแก้เครียดแป๊บ T_T

## The Final Battle — Coding

### The Rules

ในรอบนี้ แต่ละทีมจะต้องใช้โน้ตบุ๊คต่อเข้าระบบที่กรรมการเตรียมไว้ให้ เพื่อเข้าไปทำโจทย์ทั้งหมด 3 ข้อ โดยโจทย์แต่ละข้อจะถูกแบ่งออกเป็นสองส่วนคือ Small (6 คะแนน) กับ Large (9 คะแนน) ให้เวลาทำทั้งหมด 2 ชั่วโมง 30 นาที

ระหว่างการแข่งขันจะมี Scoreboard ให้ดูด้วย ยกเว้นตอนชั่วโมงสุดท้ายเท่านั้น (จะได้ลุ้น) และในกรณีที่คะแนนรวมเท่ากัน จะตัดสินจากเวลาที่ submit ข้อสุดท้ายผ่าน แต่เพื่อป้องกันการ submit มั่ว ๆ จะต้องบวกเพิ่มไป 10 นาทีทุกครั้งที่คำตอบผิด

กฎการแข่งขันคล้ายกับ Code Jam มาก แต่ไม่ต้องไปลุ้นว่า Large จะถูกหรือผิดตอนจบ contest เฉย ๆ ซึ่งก็ทำให้ผมดีใจมาก เพราะตอนแรกนึกว่าจะให้ submit ได้แค่ครั้งเดียวเหมือนตอน audition QwQ

นอกจากนี้ ระบบตรวจที่เอามาใช้คือระบบ DOMjudge ที่เอามาปรับแต่ง interface ใหม่ให้เป็นสีดำ-เขียวตาม theme ของ TechJam ซึ่งอันนี้ทำออกมาได้ดูดีมาก ๆ ครับ //ปรบมือ ๆ

อนึ่ง สำหรับในส่วน Coding นี้ ผมจะขอเล่ารายละเอียดโจทย์แต่ละข้อ รวมถึงกระบวนการคิดของผมทั้งหมดนะครับ ถ้ายาวเกินสามารถข้ามไปอ่านตรงส่วน **The End** ข้างล่างได้เลย

### Problem 1 — Max Perimeter

เมื่อเริ่มการแข่งขัน ผมจึงเปิดอ่านโจทย์ข้อแรกก่อนเป็นอย่างแรก โดยโจทย์มีใจความสรุปสั้น ๆ ว่า

{: .infobox}
> มีแท่งไม้อยู่ $N$ แท่ง แต่ละแท่งมีความยาวตามที่กำหนดให้ใน input ให้เลือกแท่งไม้มา 3 แท่ง ประกอบเป็นรูปสามเหลี่ยมที่มีพื้นที่มากกว่า 0 จงหาความยาวรอบรูปสามเหลี่ยมที่มากที่สุดที่เป็นไปได้ (Small: $N \leq 100$, Large: $N \leq 200\,000$)

เมื่ออ่านโจทย์เสร็จก็รู้สึกดีใจนิด ๆ เพราะว่าโจทย์ข้อนี้คล้ายกับโจทย์ใน programming.in.th เป็นอย่างมาก สามารถแก้ได้ง่าย ๆ โดยการ sort ความยาวแท่งไม้จากน้อยไปมาก แล้วทดลองเลือกแท่งไม้ 3 อันที่อยู่ติด ๆ กันเพื่อเช็คว่าสามารถสร้างเป็นสามเหลี่ยมได้หรือไม่ ($x+y >z$)

ผ่านไปแค่ 2 นาที **Team AquaBlitz11** ก็มีคะแนนขึ้นมาแล้ว นับว่าเป็นการเริ่มต้นที่ดี :D

### Problem 2 — Shipping Dolls

หลังทำโจทย์ข้อแรกเสร็จ ผมจึงรีบมาอ่านโจทย์ข้อที่สองต่อทันที

{: .infobox}
> มีตุ๊กตาอยู่ $N$ ตัว แต่ละตัวมีน้ำหนักตามที่กำหนดให้ใน input ต้องการแพ็คตุ๊กตาทุกตัวใส่กล่องหรือไม่ก็ถุงกระสอบ โดยมีกฎดังนี้
> - สามารถใช้กล่องกี่กล่องก็ได้ แต่ละกล่องจะรับน้ำหนักได้ไม่เกิน $L$ หน่วย
- ใช้ถุงกระสอบได้แค่ถุงเดียวเท่านั้น ถุงนี้จะรับตุ๊กตาได้ไม่เกิน $M$ ตัว
- หากตุ๊กตาตัวที่ $s$ กับ $t$ อยู่ในกล่องเดียวกัน ตุ๊กตาตัวที่ $i$ ทุกตัวที่ $s < i < t$ (ตุ๊กตาที่อยู่ระหว่างกลาง) จะต้องถูกบรรจุในกล่องใบเดียวกันด้วย หรือจะต้องถูกบรรจุลงในถุงกระสอบ
> จงหาว่าจะต้องใช้กล่องทั้งหมดกี่ใบ (Small: $N \leq 250$, Large: $N \leq 2\,500$)

อาจจะเป็นเพราะประมาทไปหน่อย คิดว่าโจทย์ข้อแรกง่ายแล้วข้อหลัง ๆ คงยากไปกว่านั้นไม่มาก ผมจึงรีบเขียน solution ข้อนี้

solution ที่เขียนไปเป็น brute force solution โดยเลือกว่าจะเอาตุ๊กตาช่วงไหนออก (ช่วงความยาว $M$) แล้วลูปนำตุ๊กตาที่เหลือใส่กล่องแบบ greedy จากซ้ายไปขวา รวม Time Complexity เป็น $\mathcal{O}(N^2)$ พอเขียนเสร็จ ส่งไปก็พบว่า… **Wrong Answer**

พอเจออย่างนี้แล้วผมจึงรีบอ่านโจทย์ซ้ำ แล้วจึงพบว่าตัวเองเข้าใจโจทย์ผิด คิดว่าตุ๊กตาที่จะเอาไปใส่กระสอบต้องอยู่ในช่วงติดกันด้วย ทั้ง ๆ ที่จะเอาตัวไหนใส่ก็ได้ O_O

โชคดีที่ไม่ได้มีทีมผมคนเดียวที่พลาด เพราะใน scoreboard จะเห็นว่า **Team ↓↓↓ Second Place ↓↓↓** ก็ได้ **Wrong Answer** ข้อนี้ไปครั้งหนึ่งเช่นกัน

แต่ในเมื่อเข้าใจโจทย์อย่างนี้แล้ว ก็ชัดเจนว่าโจทย์ข้อนี้เป็น [Dynamic Programming](https://en.wikipedia.org/wiki/Dynamic_programming) แน่นอน ผมจึงคิดสูตรขึ้นมาได้ ดังนี้

นิยามให้ $DP[i][j] =$ จำนวนกล่องที่น้อยที่สุดที่เป็นไปได้ เมื่อต้องแพ็คตุ๊กตาตัวที่ $1, 2, 3, \dots, i$ โดยอนุญาตให้นำตุ๊กตาใส่ถุงกระสอบได้แค่ $j$ ตัวเท่านั้น

ส่วน recurrence เราจะสนใจการเลือกตุ๊กตาตัวท้าย ๆ (ใกล้ ๆ ตัวที่ $i$) ใส่กล่องใบเดียว โดยสังเกตว่า

- ในกรณีปกติ เราควรจะเลือกจำนวนตุ๊กตาให้มากที่สุดเท่าที่เป็นไปได้ที่น้ำหนักยังไม่เกิน $L$

- เราอาจจะเลือกนำตุ๊กตาบางตัวออกไปใส่ถุงกระสอบได้ (ลูปเลือกจำนวนตรงนี้ ต้องไม่เกิน $j$) โดยให้นำตัวที่น้ำหนักมาก ๆ ออกไปก่อน จะทำให้สามารถเพิ่มจำนวนตุ๊กตาที่พิจารณานำใส่กล่องได้

- แล้วบวกด้วยคำตอบ $DP[x][y]$ เมื่อ $x =$ ตำแหน่งตุ๊กตาที่ไม่ได้อยู่ในกล่องนี้, $y =$ จำนวนตัวที่มีสิทธิ์นำใส่ถุงกระสอบที่เหลืออยู่

เนื่องจากว่าสูตรนี้มี $\mathcal{O}(N^2)$ state แล้วเราจำเป็นต้องลูป $\mathcal{O}(N)$ ใน transition โดยจะต้องนำตุ๊กตาตัวมากสุดออกเสมอ (อาจใช้ [priority queue](https://en.wikipedia.org/wiki/Priority_queue) ได้ใน $\mathcal{O}(\log N)$) รวมแล้วโปรแกรมจะรันใน $\mathcal{O}(N^3 \log N)$ ซึ่งผ่านแค่ Small เท่านั้น

ตอนแรกผมคิดว่าน่าจะหาวิธีที่ทำให้คำตอบของ $DP[i][j+1]$ อ้างอิงจาก $DP[i][j]$ ได้ แต่พอเขียนสูตรออกมาเป็นสัญลักษณ์ทางคณิตศาสตร์จริง ๆ ก็รู้สึกว่าน่าจะทำได้ยาก ผมจึงตัดสินใจย้ายไปทำโจทย์ข้อ 3 ก่อน

### Problem 3 — Island Counting

{: .infobox}
> กำหนดตารางขนาด $N \times M$ ให้ แต่ละช่องจะเป็นน้ำ (`.`) หรือดิน (`#`)
> - หากดินเชื่อมต่อกันในทิศทางบน-ล่าง-ซ้าย-ขวา จะถือว่าเป็นเกาะเดียวกัน
- หากดินในเกาะเดียวกันล้อมรอบน้ำไว้อยู่ จะถือว่าน้ำด้านในเป็นส่วนหนึ่งของเกาะนี้ด้วย
- ถ้ามีเกาะกลางน้ำที่โดนล้อมรอบนั้นอีก ให้ถือว่าเป็นส่วนหนึ่งของเกาะด้านนอกด้วย
> จงนับจำนวนเกาะในตารางที่กำหนดให้
(Small: $N, M \leq 300$, Large: $N, M \leq 3\,000$)

เมื่ออ่านโจทย์ข้อนี้เสร็จ ก็รู้สึกอุ่นใจขึ้นมาหน่อยเพราะคิดว่าน่าจะเป็นโจทย์ [Flood Fill](https://en.wikipedia.org/wiki/Flood_fill) บน grid graph ง่าย ๆ ทั่วไป ผมจึงรีบโค้ด solution ของผมดังนี้

![](https://cdn-images-1.medium.com/max/2000/1*3xg4w3OIW7KXItlfJS6bGw.gif)
{: .float-right}
- ให้ทำการ DFS เพื่อ fill จากขอบตาราง (ตำแหน่งด้านนอกตาราง) เข้ามาก่อน เพื่อจะได้หาว่าพื้นที่น้ำด้านนอกครอบคลุมช่องไหนในตารางบ้าง (มาร์คจุดที่เป็นพื้นที่น้ำด้านนอกด้วยสัญลักษณ์อื่น)
- หลังจากนั้น ให้ลูปหาตำแหน่งที่ยังคงเป็นเกาะอยู่ จากบนลงล่าง ซ้ายไปขวา ถ้าเจอให้ทำการ fill พื้นที่ทั้งเกาะนั้นทันที (รวมถึงพื้นน้ำด้านใน หรือเกาะที่อยู่กลางน้ำด้านในทั้งหมดด้วย)
- ทำไปเรื่อย ๆ จนกว่าจะ fill ครบทั้งหมด แล้วตอบจำนวนครั้งที่เจอเกาะใหม่

คิดว่าน่าจะถูกแล้ว พอลองส่งไปดูก็ได้ **Wrong Answer** มาอีกตัวนึง

panic สิครับทีนี้ ตอนนี้ WA มาสองข้อแล้ว เกิดอะไรขึ้นกันแน่ บัคอะไรรึป่าว ผมเลยรีบกลับไปอ่านโค้ดแล้วก็เจอจุดที่เหมือนจะบัคเล็ก ๆ น้อย ๆ พอลองแก้ดู ส่งไปก็ **Wrong Answer**

ใช้เวลาอยู่สักพักจึงตั้งสติได้แล้วลองคิด test case มั่ว ๆ ขึ้นมา ตั้งแต่เคสแรกที่คิดขึ้นมาเองได้ ก็พบจุดผิดแล้ว

```
4 4
.#.#
#.#.
.#.#
#.#.
```

test case นี้ควรตอบว่ามี 8 เกาะ แต่โปรแกรมผมดันตอบ 4 เพราะหลัง flood fill พื้นที่น้ำด้านนอก จะได้ตารางแบบนี้

```
!#!#
#.#!
!#.#
#!#!
```

แล้วพอลูปเพื่อหาตำแหน่งที่เป็นเกาะโดย flood fill พื้นดินและน้ำทุกครั้งที่เจอเกาะใหม่ โปรแกรมจะคิดว่าพื้นที่ดินกับน้ำตรงกลางทั้งหมดเป็นเกาะเดียวกัน (เกาะ A ตามตารางด้านล่างนี้)

```
!A!B
AAA!
!AAA
C!A!
```

นั่นแปลว่าแนวคิดการ fill น้ำและดินด้านในเพื่อป้องกันการนับเกาะด้านในซ้ำ **ผิด**! ผมจึงคิดไอเดียใหม่ได้ นั่นก็คือ

- ตอน fill จากขอบตารางเข้าไป ถ้าเจอตรงไหนที่เป็นดิน ให้จดตำแหน่งไว้ด้วยว่าเป็นตำแหน่งที่น่าสนใจ (เพราะฉะนั้น ดินตรงกลางด้านในจะไม่ถูกนับ)

- พอ fill เสร็จ ให้ fill พื้นที่ดินที่อยู่ติดกับตำแหน่งที่น่าสนใจแต่ละตำแหน่งแล้วนับจำนวน component (ไม่ต้อง fill ผ่านพื้นที่น้ำอีกแล้ว เพราะเรารู้ว่าเกาะตรงกลางด้านในจะไม่ถูกนับแน่ ๆ)

แต่เมื่อส่งไปก็ **Wrong Answer** อีก T_T

มาถึงตอนนี้ **Team ↓↓↓ Second Place ↓↓↓** ทำข้อนี้ ได้คะแนนนำผมไปแล้ว ผมจึงกลับไปอ่านโจทย์อีกครั้ง เผื่อว่าเข้าใจโจทย์ผิดเหมือนข้อที่ผ่านมา

แล้วมันก็เป็นอย่างนั้นจริง ๆ ด้วย ผมเพิ่งเห็น Sample Test Case 2 ตามนี้

```
7 7
.......
..####.
.#...#.
.#.#.#.
.#...#.
.#####.
.......
```

โจทย์บอกว่าต้องตอบ 2 แต่ผมเข้าใจว่าต้องตอบ 1 เพราะคิดว่าพื้นที่น้ำตรงกลางเป็นส่วนหนึ่งของเกาะด้านนอก แต่ไม่เลย **เกาะด้านนอกยังล้อมรอบไม่สนิท ไม่นับว่าพื้นที่น้ำตรงกลางเป็นส่วนหนึ่งของเกาะด้านนอก**

พอรู้ตัวอย่างนี้แล้วก็เครียดเลย เพราะโจทย์ข้อนี้ดูยากกว่าที่คิดมาก หลังจากนั่งคิดวิธีแก้ไปประมาณ 2–3 นาทีก็เพิ่งนึกได้ว่า เฮ้ย เอาจริง ๆ วิธีล่าสุดก็ถูกแล้ว แค่ตอน fill พื้นที่ด้านนอก ให้มัน fill เฉียงได้ด้วยเท่านั้นเอง (เพราะฉะนั้นพื้นที่น้ำด้านในก็จะถือว่าเป็นพื้นที่เดียวกับขอบตารางด้านนอก)

แก้เพียงแค่นั้นก็ได้ผลลัพธ์ออกมาเป็น **Correct** สีเขียวที่อุตส่าห์รอมานานแสนนาน ข้อนี้ไม่ได้ยากอะไรเลย สะเพร่าเอง T_T

### Revisiting Problem 2 — Shipping Dolls

ในตอนแรก สูตร Dynamic Programming ที่ผมคิดไว้ จำเป็นต้องหาวิธีลดเวลาจาก $\mathcal{O}(N^3 \log N)$ ให้เหลือ $\mathcal{O}(N^2)$ หรือ $\mathcal{O}(N^2 \log N)$ แต่เมื่อดูดี ๆ แล้ว คิดว่าน่าจะไม่มีวิธีง่าย ๆ ดังนั้นผมจึงต้องเปลี่ยนนิยาม DP ใหม่

แผนในหัวผมก็คือ น่าจะหาวิธีนิยาม DP ยังไงก็ได้ให้มันมีคุณสมบัติ monotonicity ของชอยส์ใน recurrence แล้วใช้ [divide & conquer optimization](https://www.quora.com/What-is-divide-and-conquer-optimization-in-dynamic-programming) แก้เอา แต่ความรู้สึกอีกอย่างนึงคือ

**"โจทย์มันไม่น่าต้องใช้เทคนิคยากขนาดนี้"**

อะ แต่ช่างมัน ใช้เทคนิคยากเกินไปหน่อยจะเป็นไร ถ้ามันทำให้ได้คะแนนก็ถือว่าโอเคแล้ว

นิยามให้ $DP[i][j] =$ จำนวนตัวที่จะต้องนำใส่กระสอบที่น้อยสุดที่เป็นไปได้ เมื่อต้องการแพ็คตุ๊กตาตัวที่ $1$ ถึง $j$ ใส่กล่องไม่เกิน $i$ กล่อง

เมื่อนิยามอย่างนี้แล้ว คำตอบสุดท้ายคือค่า $x$ น้อยสุดที่เป็นไปได้ที่ $DP[x][N] \leq M$ (นำใส่ $x$ กล่องได้โดยต้องนำตุ๊กตาใส่กระสอบไม่เกิน $M$ ตัว)

ส่วน recurrence ก็สามารถคิดได้ง่ายขึ้น เพราะรูปแบบสูตรจะคล้ายกับพวก partitioning problem (แบ่ง array ความยาว $N$ ออกเป็น $K$ ช่วง) นั่นคือ เราต้องลูปตำแหน่ง $1 \leq k \leq j$ เพื่อหาว่าควรให้ช่วงสุดท้าย (ช่วง $[k..j]$) เป็นช่วงใดจึงจะได้คำตอบดีสุด นั่นคือ

$$DP[i][j] = \min_{1 \leq k \leq j}\left(DP[i-1][k-1] + F(k, j)\right)$$

โดย $F(k, j) =$ จำนวนตุ๊กตาน้อยสุดที่ต้องนำใส่กระสอบ (สนใจเฉพาะตัวที่ $k$ ถึง $j$ เท่านั้น) เพื่อให้ผลรวม $\leq L$ ซึ่งส่วนนี้เราสามารถ precompute ไว้ได้ใน $\mathcal{O}(N^2 \log N)$ (fix จุดเริ่มต้นแล้วไล่เพิ่มผลรวมไปทางขวา หากผลรวมเกินก็ให้นำตัวมากสุดออกจาก priority queue)

ส่วนสูตร DP นี้ ถึงแม้ว่าจะเป็นสูตร $\mathcal{O}(N^3)$ แต่จากข้อสันนิษฐานว่า

* ถ้าให้ตำแหน่ง $k$ ที่ดีที่สุดของ $DP[i][j]$ เป็น $K[i][j]$ จะพบว่า $K[i][j] \leq K[i][j+1]$ สำหรับทุก $j$ ที่ $1 \leq j < N$ (monotonicity)

จากคุณสมบัตินี้ เราสามารถใช้ [divide & conquer optimization](https://www.quora.com/What-is-divide-and-conquer-optimization-in-dynamic-programming) ลดเวลาให้เหลือ $\mathcal{O}(N^2 \log N)$ ได้ ซึ่งก็จะทำให้ได้คะแนนในโจทย์ข้อนี้พอดี

**แน่นอนว่าชีวิตมันไม่ได้ง่ายขนาดนั้น**

เพราะเมื่อผมส่งโค้ดไปแล้ว พบว่ากลับได้คำตอบมาเป็น Wrong Answer ซะงั้น O_O ผมจึงลองปรับโค้ดกลับเป็นโค้ดเวอร์ชัน $\mathcal{O}(N^3)$ ที่ไม่ได้ใช้คุณสมบัตินี้ดูแล้ว แล้วให้โปรแกรมมันเช็คคุณสมบัตินี้ด้วยตัวเองดู พบว่า

เอาจริง ๆ แล้วคุณสมบัตินี้มันผิดตั้งแต่ Sample Test Case แล้วล่ะ T_T

แต่ไม่เป็นไร อย่างน้อยไหน ๆ ก็ปรับโค้ดแล้ว ผมจึงส่งโค้ด $\mathcal{O}(N^3)$ ไปตรวจในระบบ เลยได้ **Correct** ใน Small Test Set มาให้อุ่นใจนิดนึง หลังจากนั้นไม่นาน **Team ↓↓↓ Second Place ↓↓↓** ก็ submit solution คล้าย ๆ กัน ทำให้คะแนนผมตกลงมาเป็นอันดับ 2 อีกครั้ง (เอาจริง ๆ คะแนนเท่ากัน แต่ข้อ 3 ผม submit ผิดหลายครั้งเลยโดนบวก penalty เยอะกว่า)

หลังจากนั่งงมไปสักพัก พยายามคิดสูตร DP ต่าง ๆ มากมายที่น่าจะหาวิธี optimize ได้ ผมก็นึกขึ้นได้ว่า เฮ้ย เอาจริง ๆ เราไม่จำเป็นต้องใช้คุณสมบัตินี้เต็มที่ก็ได้ อาจจะอนุญาตให้มันเขยิบ ๆ ได้นิดนึง เช่น ถ้าสมมุติเรารู้ว่า $K[i][j]$ ควรมีค่าอยู่ระหว่าง $x$ กับ $y$ ก็ลองขยายช่วงให้มันเป็น $x-10$ ถึง $y+10$ ดู

เอาจริง ๆ ก็ไม่คิดว่ามันจะถูกแหละ แต่พอส่งไป…

**Correct**

ผ่านแบบงง ๆ ตอนเหลือเวลาประมาณ 30–40 นาทีก่อนจบการแข่งขัน (Scoreboard โดน freeze ไปแล้ว ทีมอื่นเลยไม่เห็นว่าผ่าน)

แต่นี่ไม่ใช่ Correct ที่รู้สึกดีเท่าไหร่นัก เพราะยังรู้สึกไม่ค่อย convinced ว่าวิธีนี้ใช้ได้ทุกกรณีจริง (ถึงแม้จะผ่าน test case ในงานแข่งแล้วก็เถอะ) ผมเลยใช้เวลาที่เหลือพยายามนั่งคิดวิธีไปเรื่อย ๆ แต่ก็คิดไม่ออก

![](https://cdn-images-1.medium.com/max/350/1*6YfKbBKSyZsFbhtR0b_ygQ.jpeg)
{: .float-right}
(เอาจริง ๆ แล้วข้อนี้มี solution $\mathcal{O}(N^2)$ ง่าย ๆ อยู่ กำหนดให้ $DP[i][j] =$ จำนวนกล่อง และน้ำหนักในกล่องสุดท้ายที่น้อยที่สุดที่เป็นไปได้ เมื่อแพ็คตุ๊กตาที่ $1$ ถึง $i$ โดยนำใส่ถุงกระสอบไม่เกิน $j$ ตัว — ส่วน recurrence ก็แค่เลือกว่าจะนำตัวที่ $i$ ใส่กระสอบ หรือว่าจะเอาไปรวมกับตัวก่อน ๆ หน้า ถ้าน้ำหนักเกินให้เพิ่มจำนวนกล่อง)

ในขณะเดียวกัน ช่วงครึ่ง ชม. สุดท้ายเป็นช่วงที่ทรมาณที่สุด เพราะผมต้องคอยลุ้นว่า **Team ↓↓↓ Second Place ↓↓↓** จะผ่านหรือไม่ผ่าน ถ้าเขาผ่านผมจะได้ที่ 2 แต่ถ้าเขาไม่ผ่านผมจะได้ที่ 1

หลังจากนั่งลุ้นไปยาว ๆ ตอน 10 นาทีก่อนการแข่งขันก็พบว่า คนในทีมทั้งสองคน high five กันด้วยสีหน้ายิ้มแย้ม แถมหน้าจอโน้ตบุ๊คเหมือนจะเห็นเป็นสีเขียว ๆ

ทำผ่านกันแล้วสินะ… T_T

## The End

หลังจบ contest แล้ว ผมจึงลุกขึ้นไปคุยกับ **Team ↓↓↓ Second Place ↓↓↓** ว่าทีมนั้นใช้วิธีไหนจึงผ่านโจทย์ข้อนี้ได้ พบว่า…

เยดเข้ ใช้วิธีเกรียนเหมือนกันเลยนี่หว่า O_O"

แต่อย่างน้อยการแข่งขันในครั้งนี้ก็ไม่ใช่การแข่งขันง่าย ๆ อย่างที่คิดไว้ตอนแรก การมาเยือนของทีมมหาเทพช่วยให้การแข่งขันครั้งนี้สนุกขึ้นเยอะ คิดว่าคำที่เหมาะสมที่สุดตอนนี้ก็คงจะเป็น **Good game :D** แหละนะ

ส่วน **Team PlugFire** รุ่นพี่ผมจาก มช. บอกว่าข้อที่ 2 "ขี้เกียจทำ เพราะไม่ชอบอยู่ที่ 1 เดี๋ยวได้หน้าลงเพจ" แต่ดูเหมือนโชคจะไม่เข้าข้าง เพราะทีมอื่นทำคะแนนข้อนี้ไม่ได้เช่นกัน ถ้าคะแนนรอบ Quickfire และ Ponder ดีก็คงจะได้ขึ้นหน้าเพจอยู่ดีแหละนะ :D

### Closing Ceremony

ในส่วนของพิธีปิด จะเป็นการมอบเกียรติบัตรให้กับผู้เข้าแข่งขันแต่ละคน ทั้งใน Code Squad และ Data Squad แล้วจึงมอบรางวัลให้กับ Top 3 ของแต่ละ Squad โดยมีรางวัลดังนี้

* โล่รางวัลที่มีสัญลักษณ์ Squad กับหมายเลขอันดับประดับอยู่อย่างเวอร์วังอลังการสวยงาม

* (ป้าย) เงินรางวัล โดยอันดับ 1, 2, 3 จะได้เงินรางวัล 30K, 20K, 10K ตามลำดับ

* Badge ประจำ Squad ที่เอาไว้เย็บติดเสื้อหรือกระเป๋า

ซึ่งตามที่คาดไว้ ในสาย Code Squad พบว่าทีมที่ผมรู้จักและพูดถึงมาตลอดบล็อกนี้ ได้รางวัลทั้งสามทีมเลย นั่นก็คือ…

* **อันดับ 3 —** **Team PlugFire** ทีมของพี่ ๆ จาก มช. นั่นเอง

* **อันดับ 2 — Team AquaBlitz11** ทีม solo ของผมเอง

* **อันดับ 1 —** **Team ↓↓↓ Second Place ↓↓↓** ทีมมหาเทพผู้แทน IOI ที่รู้อยู่แล้วว่าได้ที่ 1 แน่นอน \_/\\\_ #กราบ

รับรางวัลเสร็จแล้ว สุดท้ายก็ถ่ายรูปรวมเก็บเป็นที่ระลึก ทั้งรูปผู้ชนะแต่ละ Squad และรูปผู้ชนะทุก Squad เลย ถือว่าเป็นบทสรุปของการแข่งขัน TechJam 2018 Regional Competition ในภาคเหนือแล้วนั่นเองครับ ที่เหลือก็แค่รอประกาศผลเข้าแข่งระดับประเทศเพียงเท่านั้น~

## Final Words

สุดท้ายแล้วรางวัลที่ได้รับก็ไม่ใช่สิ่งที่สำคัญที่สุดในการแข่งขันนี้ แต่กลับเป็นประสบการณ์และความรู้ที่ได้รับจากการแข่งขันต่างหาก สำหรับผู้เข้าแข่งขันบางคน ความรู้ที่ได้รับก็คือพวกเทคนิค Algorithms และ Data structures ต่าง ๆ ที่ตนเองอาจจะยังไม่เคยเจอมาก่อน แต่ถึงแม้จะเคยเจอมาก่อนแล้ว อีกอย่างหนึ่งที่ปฏิเสธไม่ได้แน่ ๆ คือการที่มาเข้าร่วมการแข่งขันจะช่วยให้เราขัดเกลาจุดอ่อนและพัฒนาจุดแข็งได้ยิ่งขึ้น

ได้ยินมาว่าเดิม TechJam 2017 จัดแค่เพียงภาคกลางเท่านั้น ส่วน TechJam 2018 เป็นครั้งแรกที่ขยายมาจัดในภาคอื่น ๆ รวมถึงภาคเหนือด้วย ผมจึงได้มีโอกาสเข้าร่วมการแข่งขันเขียนโปรแกรมที่ลงทุนจัดจริงจังขนาดนี้ ไม่ว่าจะเป็นเรื่องเหล่า staff ที่เผลอ ๆ อาจจะมีจำนวนเยอะกว่าผู้เข้าแข่งขัน O_O" เรื่องอาหาร ของที่ระลึก หรือแม้กระทั่งบรรยากาศที่หาไม่ได้ในงานอื่นอีกแล้ว

ผมขอขอบคุณทาง KBTG และทางทีมงานที่จัดการแข่งขันดี ๆ อย่าง TechJam 2018 ไว้ ณ ที่นี้ด้วยนะครับ หวังว่าจะมีการแข่งขันนี้ที่พัฒนาต่อไปเรื่อย ๆ ในอนาคต เป็นเวทีแสดงศักยภาพ และเป็นแหล่งจุดประกายสร้างความรู้ความสามารถให้กับเหล่า developer ในประเทศไทยต่อไปครับ

{: .figure}
> ![](https://cdn-images-1.medium.com/max/3752/1*BLo7AKmgI1DxGQTgftrG2A.jpeg)
>
> ผู้เข้าแข่งขัน TechJam 2018 Regional Competition ภาคเหนือทั้งหมด

