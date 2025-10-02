# BAI_TAP_PYTHON_THAY_THUONG_PTIT
Các bài tập cơ bản về python
# BÀI TẬP THẦY THƯƠNG GIAO (2/10/2025) 

# 2.2. VÀO RA TRONG PYTHON
# In ra một chuỗi   
print('Hoàng xin chào các bạn')

# In ra nhiều đối tượng
print('Khoa học', 'Pháp luật', 'Trí tuệ', sep=',', end='!\n\n')

# In ra một tuple
x = ('Em', 'cảm', 'ơn')
print(x)

# Yêu cầu người dùng nhập tên
name = input('Nhập tên của bạn: ')
print('Chào các bạn, mình tên là', name)

# Yêu cầu người dùng nhập một số nguyên
so1 = int(input('Điền một số nguyên: '))
print ('Số nguyên bạn đã nhập là: ', so1)

# Yêu cầu người dùng nhập số 
so1 = int(input('Nhập số thứ nhất: '))
so2 = int(input('Nhập số thứ hai: '))
# Tính tổng
tong = so1 + so2
# In kết quả
print('Tổng của', so1,'và', so2, 'là: ', tong)

# Yêu cầu nhập nhiều giá trị trên một dòng
much = input('Nhập các giá trị cách nhau bằng khoảng trắng').split()
print('Các giá trị nhập là: ', much)

# 2.3. TOÁN TỬ
# Toán tử số học
print('Toán tử số học')
a = 24
b = 8

print('a + b = ',a+b)
print('a - b = ',a-b)
print('a * b = ',a*b)
print('a / b = ',a/b)
print('a % b = ',a%b)
print('a ** b = ',a**b)
print('a // b =',a//b)

# Toán tử so sánh
print('Toán tử so sánh')
a = 12
b = 36

print('a == b',a == b)
print('a != b',a != b)
print('a > b',a > b)
print('a < b',a < b)
print('a <= b',a <= b)
print('a >= b',a >= b)

# Toán tử gán
print('Toán tử gán')
a = 2007

a += 18
print('a += 18 =', a)

a -= 7
print('a -= 7 =', a) 

a *= 2
print('a *= 2 =', a)

a /= 3
print('a /= 3 =', a)

a %= 9
print('a %= 9 =', a)

a **= 2
print('a **= 2 =', a)

a //= 3
print('a //= 3 =', a)

# Toán tử logic
a = True
b = False

print('a and b', a and b)
print('a or b', a or b)
print('not a', not a)

# 3.0. CẤU TRÚC LỆNH RẼ NHÁNH (if, else, elif)
# If - Else
print('If - Else')
age = 18
if age >= 18:
    print('Bạn đủ tuổi để đi tù')
else:
    print('Bạn chưa đủ tuổi đi tù')

# If - Elif - Else
print('If - elif - else')
score = 88

if score >= 90:
    print(" A+ ")
elif score >= 80:
    print(" A ")
elif score >= 70:
    print(" B ")
elif score >= 60:
    print(' C ')
else:
    print(" D ")

# Kết quả điều kiện với các toán tử logic
print('Kết quả điều kiện với các toán tử logic')
age = 18
citizen = 'VIETNAMESE'

if age >= 18 and citizen == 'VIETNAMESE':
    print('Bạn đi tù')
else:
    print('Bạn không đi tù')

# Ứng dụng điều kiện với các kiểu dữ liệu khác nhau
print('So sánh giá trị')

x = 24
y = 8

if x > y:
    print('x lớn hơn y')
elif x < y:
    print('x bé hơn y')
else:
    print('x bằng y')

# Đánh giá điểm thi 
diem = float(input('Nhập điểm của bạn: '))

if diem >= 9:
    print('A+ - 4.0 - Xếp loại giỏi')
elif diem >= 8.5:
    print('A - 3.7 - Xếp loại giỏi')
elif diem >= 8:
    print('B+ - 3.5 - Xếp loại khá')
elif diem >= 7:
    print('B - 3.0 - Xếp loại khá')
elif diem >= 6.5:
    print('C+ - 2.5 - Xếp loại trung bình')
elif diem >= 5.5:
    print('C - 2.0 - Xếp loại trung bình')
elif diem >= 5:
    print('D+ - 1.5 - Xếp loại trung bình yếu')
elif diem >= 4:
    print('D - 1 - Xếp loại trung bình yếu')
else:
    print ('F - 0 - Xếp loại kém')