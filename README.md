#1.
a = int(input("輸入一個數字"))
while(a>1000 or a<0):
    print("重輸一次")
    a = int(input("輸入一個數字"))
b = a%2
if b == 0:
    print("是偶數")
else:
    print("是奇數")
#2
a = int(input("請需要建立幾次模板故事"))
for b in range(a):
    num = int(input("請輸入課程期數"))
    class_name = input("請輸入課程名稱")
    name = input("請輸入姓名")
    background = input("請輸入你的背景(科系或職業)")
    hope = input("請簡述對於本課程的期望(列出幾點修完課程想得到的技能/對自己未來的規劃)")

    print(f"第{num}期-{class_name}")
    print(f"姓名:{name}")
    print(f"學生背景: {background}")
    print("==================================")
    print(f"{name} 修習完課程[{class_name}]後，")
    print(f"結業獲得{hope}。")
    print("well done")
#3

