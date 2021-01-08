Grey_Code_Generator
print("Tipe's of number:")
print("1 - Decimal number system")
print("2 - Binary number system")
print("Choose your number tipe:")
a = int(input())
if a == 1:
    print("Choose your number (0-15): ")
    b = int(input())
    if b == 0:
        print("Your Grey Code = 0000")
    if b == 1:
        print("Your Grey Code = 0001")
    if b == 2:
        print("Your Grey Code = 0011")
    if b == 3:
        print("Your Grey Code = 0010")
    if b == 4:
        print("Your Grey Code = 0110")
    if b == 5:
        print("Your Grey Code = 0111")
    if b == 6:
        print("Your Grey Code = 0101")
    if b == 7:
        print("Your Grey Code = 0111")
    if b == 8:
        print("Your Grey Code = 1100")
    if b == 9:
        print("Your Grey Code = 1101")
    if b == 10:
        print("Your Grey Code = 1111")
    if b == 11:
        print("Your Grey Code = 1110")
    if b == 12:
        print("Your Grey Code = 1010")
    if b == 13:
        print("Your Grey Code = 1011")
    if b == 14:
        print("Your Grey Code = 1001")
    if b == 15:
        print("Your Grey Code = 1000")
if a == 2:
    print("Choose your natual binary number (0-15 in binary system): ")
    c = int(input())
    if c == 0000:
        print("Your Grey Code = 0000")
    if c == 1:
        print("Your Grey Code = 0010")
    if c == 10:
        print("Your Grey Code = 0001")
    if c == 11:
        print("Your Grey Code = 0011")
    if c == 100:
        print("Your Grey Code = 1000")
    if c == 101:
        print("Your Grey Code = 1010")
    if c == 110:
        print("Your Grey Code = 1001")
    if c == 111:
        print("Your Grey Code = 1011")
    if c == 1000:
        print("Your Grey Code = 0100")
    if c == 1001:
        print("Your Grey Code = 0110")
    if c == 1010:
        print("Your Grey Code = 0101")
    if c == 1011:
        print("Your Grey Code = 0111")
    if c == 1100:
        print("Your Grey Code = 1100")
    if c == 1101:
        print("Your Grey Code = 1110")
    if c == 1110:
        print("Your Grey Code = 1101")
    if c == 1111:
        print("Your Grey Code = 1111")
