try:
    s = int(input('Please input score : '))
except:
    s = 0

if s >= 90:
    print('4.0')
elif s >= 85:
    print('3.5')
elif s >= 80:
    print('3.0')
elif s >= 75:
    print('2.5')
elif s >= 70:
    print("2.0")
elif s >= 65:
    print('1.5')
elif s >= 50:
    print('1.0') 
else:
    print("ตก")
