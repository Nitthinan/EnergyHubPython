# โปรแกรมฝึกพิมพ์ " Pimsampas" version 0.1 (pimsampas)

### วิธีติดตั้ง

เปิด CMD / Terminal

```python
pip install energyhubpython
```

### วิธีเล่น

เปิด IDLE ขึ้นมาแล้วพิมพ์...

```python
>>> from energyhubpython import Student, SpecialStudent
print('=======2021, 1 Jan=======')
student0 = SpecialStudent('Mark Zuckerberg','Bill Gates')
student0.AskEXP()
student0.ShowEXP()

student1 = Student('Albert')
print(student1.name)
student1.Hello()
print('----------------------')

student2 = Student('Steve')
print(student2.name)
student2.Hello()
print('----------------------')

print('ตอนนี้ exp ของแต่ละคนได้เท่าไหร่กันแล้ว')
student1.ShowEXP()
student2.ShowEXP()

print('=======2021, 2 Jan=======')
print('---ใครอยากเรียนโค้ดดิ้ง ?---+10 exp---')
student1.AddEXP(10)
print('ตอนนี้ exp ของแต่ละคนได้เท่าไหร่กันแล้ว')
student1.ShowEXP()
student2.ShowEXP()

print('=======2021, 3 Jan=======')
print('ตอนนี้ exp ของแต่ละคนได้เท่าไหร่กันแล้ว')
student1.ShowEXP()
student2.ShowEXP()

print('=======2021, 4 Jan=======')
for i in range (5):
student2.Coding()

print('ตอนนี้ exp ของแต่ละคนได้เท่าไหร่กันแล้ว')
student1.ShowEXP()
student2.ShowEXP()

พัฒนาโดย: EnergyHubThailand
