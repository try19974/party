# Name Party List จัดรายชื่อคนมางาน
ฉันกับเพื่อนจะจัดงานปาร์ตี้แต่คนละวัน แต่เนื่องจากกลุ่มที่จะมาเป็นกลุ่มเดียวกัน ฉันเลยเป็นคนนั่งพิมพ์ รายชื่อเพื่อนที่จะมา พอเพื่อนเห็น เลยขอก๊อปปี้รายชื่อไป ฉันจะเอาไปใช้จัดงานของตัวเอง
แต่เนื่องจากคนมางานไม่เหมือนของฉันทั้งหมดจึงต้องไปตัดและเพิ่มเอง

### งานที่จะให้ทำคือ

ตัดรายชื่อและเพิ่มชื่อในรายชื่อของเพื่อน และแสดงรายชื่องานของฉันและเพื่อน

# Input
  * `name_party_me` listชื่อคนที่มางานฉัน
  * `name_party_remove` คนที่จะไม่มางานเพื่อน
  * `name_party_add` คนที่จะมางานเพื่อนเพิ่ม
### ถ้าคนที่จะให้เอาออกแล้วไม่เจอใน`name_party_me` ให้คืนค่า Error
# Output
  * `name_party_me`รายชื่อคนงานของฉัน
  * `name_party_friend`รายชื่อคนมางานเพื่อน
# Function
```python
def listparty(name_party_me,name_party_remove,name_party_add):
    name_party_me=[]
    name_party_friend=[]
    return [name_party_me,name_party_friend]
```
# Example
### Input
```python
listparty(["A","B","C","D","E","F","G","H","I","J"],[A],["k","L"])
```
### Output
```python
['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J']
['B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L']

