# test code
```import numpy as np
a=np.array([1,2,3,4,5,6,7,8,9])
print(a.shape)
b=a[np.newaxis,:] #row wise
print(b,b.shape)
b=a[:,np.newaxis]#colume axis
print(b)
```