1.
  n = int(input("Enter the value of 'n': "))
  a = 0
b = 1
sum = 0
count = 1
print("Fibonacci Series: ", end = " ")
while(count <= n):
  print(sum, end = " ")
  count += 1
  a = b
  b = sum
  sum = a + b
Enter the value of 'n': 
5


2​
f = open("one.dat","wb")
arr = bytearray("i love Letsupgrade".encode("utf8"))
f.write(arr)
f.close()
​
f = open("one.dat","rb")
print = (f.read())
f.close(
    
f = open("one.dat","a+")
f.write("/nwe all love python class with Lu")
​
