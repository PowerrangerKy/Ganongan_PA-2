Normalization Problem
''' python
#start
#Use to Import numerical python Library
import numpy as np

#Create the randon 5x5 array:
X = np. random. rand(5, 5)

#Formula for the Noralized Values
Z = (X - X.mean()) /X.std() 

#save Normalized values as X_nomatized. ny
np. save("X_normalized.npy", Z) 

#Publish the original value of "Z" along with the original value of "X"
print ("Original Value: \n", X, "\n Normalized Value: \n", Z) 
#end
Original Value: 
 [[0.24571014 0.58214871 0.69121124 0.42748001 0.06073605]
 [0.5523521  0.40589269 0.93307028 0.75329159 0.27531718]
 [0.76066187 0.18454118 0.75311866 0.56060821 0.16599602]
 [0.35634079 0.73513495 0.70388063 0.97526841 0.67346679]
 [0.81760001 0.04888914 0.05131004 0.82144206 0.99589248]] 
 Normalized Value: 
 [[-1.00719472  0.13936483  0.51104244 -0.38773546 -1.6375737 ]
 [ 0.03782004 -0.46130357  1.33528144  0.72260801 -0.90629593]
 [ 0.74772541 -1.21565431  0.72201866  0.06595629 -1.27885495]
 [-0.63017305  0.66073143  0.55421886  1.47908976  0.45057056]
 [ 0.94176669 -1.67794715 -1.66969688  0.95486012  1.54937517]]
'''

 Division by 3 problem
 ''' python
#start
#Use to Import numerical python Library
import numpy as np

#Make an array with the first 100 positive numbers in it
A = np.array(np.arange (1,101,1))

#Make the array 10 by 10 in size
A. resize (10,10)

#creates a new array and squares each entry on its own
Squared_A = np. square (A)

#saves each Squared A element that is divisible by 3
Div_by_3 = Squared_A[A&3==0]

#Put an array in 'div_by_3.npy*' that has entries that can be divided by 3
np.save ('div_by_3.npy', Div_by_3)

#end
A

array([[  1,   2,   3,   4,   5,   6,   7,   8,   9,  10],
       [ 11,  12,  13,  14,  15,  16,  17,  18,  19,  20],
       [ 21,  22,  23,  24,  25,  26,  27,  28,  29,  30],
       [ 31,  32,  33,  34,  35,  36,  37,  38,  39,  40],
       [ 41,  42,  43,  44,  45,  46,  47,  48,  49,  50],
       [ 51,  52,  53,  54,  55,  56,  57,  58,  59,  60],
       [ 61,  62,  63,  64,  65,  66,  67,  68,  69,  70],
       [ 71,  72,  73,  74,  75,  76,  77,  78,  79,  80],
       [ 81,  82,  83,  84,  85,  86,  87,  88,  89,  90],
       [ 91,  92,  93,  94,  95,  96,  97,  98,  99, 100]])
'''
