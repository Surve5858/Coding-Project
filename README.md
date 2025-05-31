
class Polynomial:
    def __init__(self):
        self.list1 = [0, 0, 0]

    def plus(self):
        deg1 = int(input("Enter degree 1: "))
        for i in range(0, deg1 + 1):
            self.list1[i] += int(input("Enter your number: "))

    def co(self):
        print(int(self.list1.count(0)))

    def __str__(self):
        return str(self.list1)


deg = int(input("Enter degree: "))
list_ = [0, 0, 0]

for i in range(0, deg + 1):
    list_[i] = int(input("Enter your number: "))

p1 = Polynomial()
p1.list1 = list_

print(str(p1))
p1.plus()
print(str(p1))
p1.co()
