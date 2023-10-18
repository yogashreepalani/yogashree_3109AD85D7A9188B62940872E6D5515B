#1.2 write a program that determine whether a year entered by user is a leap year or not
year=2025
# to get year (integer input ) from the user
# year=int(input("Enter the year: "))
# divided by 100 means century year(ending with 00)
if ( year%400) and ( year%100)==0:
    print("Leap year{0}is leap year".format(year))
  #not divided by 100 means not century year
# year divided by 4 is a leap year
elif ( year%4)==0:
    print("Leap year{0}is leap year".format(year))
else:
    print("{0} is not a leap year".format(year))