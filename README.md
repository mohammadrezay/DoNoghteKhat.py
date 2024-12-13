# DoNoghteKhat.py
https://quera.org/problemset/3414?tab=description
string = input().split()

if string[0] == string[2]:
    print("Vertical")
elif string[1] == string[3]:
    print("Horizontal")
else:
    print("Try again")
