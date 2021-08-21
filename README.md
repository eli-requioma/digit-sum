# digit-sumdef digit_sum(n):
    digits = list(str(n))
    total = 0
    for i in range(len(digits)):
        total += int(digits[i])
    return total

print(digit_sum(3**99))
