#program Python untuk membebani kesetaraan
#dan kurang dari operator
class A:
  def __init__(self,a):
    self.a=a
  def __it__(self,lain):
    if(self.a<lain.a):
      return "objek1 kurang dari objek2"
    else:
      return "objek2 kurang dari objek1"
  def __eq__(self,lain):
    if(self.a==lain.a):
      return "keduanya sama"
    else:
      return "tidak sama"
objek1=A(2)
objek2=A(3)
print(objek1<objek2)

objek3=A(4)
objek=A(4)
print(objek1==objek2)
