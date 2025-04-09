x = 10
y = 30

# Nested if statements
if x < y:
    print('x is less than y')
else:
    if x > y:
        print('x is greater than y')
    else:
        print('x and y are equal')

# Equivalent code using elif
if x < y:
    print('x is less than y')
elif x > y:
    print('x is greater than y')
else:
    print('x and y are equal')
