# 1.python-movie-rating
Write a program using conditional statements on Movie Ratings by taking user input


rating = float(input("enter the values :"))
if rating <0 or rating >5:
    print("pls enter the valid rating")
elif rating<= 5 and rating >= 4.5:
    print("movie is blockbooster")
elif rating >4:
    print("movie is superhit")
elif rating >3.5:
    print("movie is hit")
elif rating >3:
    print("movie is good")
elif rating >2.5:
    print("movie is average")
else:
    print("movie is flop")

#output
PS E:\python> python tasks.py
enter the values :223
pls enter the valid rating
PS E:\python> python tasks.py
enter the values :1 
movie is flop
PS E:\python> python tasks.py
enter the values :12345678
pls enter the valid rating
PS E:\python> python tasks.py
enter the values :4
movie is hit
