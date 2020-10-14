#Python-Matrix
matrix = "X"
X = [[1,2,3],
    [4,5,6],
    [7,8,9]]
print(type(X))

matrix = "Y"
Y = [[10,11,12],
    [13,14,15],
    [16,17,18]]
print(type(Y))

result = [[0,0,0],
         [0,0,0],       
         [0,0,0]]
         
for i in range(len(X)):
   for j in range(len(Y[0])):
      for k in range(len(Y)):
         result[i][j] = X[i][k] * Y[k][j]

for r in result:
   print(type(r))
