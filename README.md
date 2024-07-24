total=10
sale=int(input("enter the no.of candies:"))
if sale>0 and sale<=5:
    print("NUMBER OF CANDIES SOLD:",sale)
    print("NUMBER OF CANDIES AVAILABLE:",total-sale)
else:
    print("INVALID INPUT")
    print("NUMBER OF CANDIES AVAILABLE:",total)
