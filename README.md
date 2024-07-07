# Filter()
# python program to print the sum of squares.
def squares(x):
    return(x**2)
    squares=[]
squares=list(filter(squares,range(1,11)))
print(squares)
sum=0
for i in squares:
    sum+=i**2
print(sum)


# output
[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
385
