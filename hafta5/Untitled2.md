```python
#Sayılardan oluşan bir boyutlu array oluşturun. Arrayi oluştururken sayıların veri tipini integer olarak belirtelim.

#Oluşturulan arrayin boyut, eleman sayısı bilgilerine bakalım.
import numpy as np
array = np.array([1,2,3,4,5], dtype="int")
print(array)
```

    [1 2 3 4 5]
    


```python
print(array.ndim)
```

    1
    


```python
print(array.size)

```

    5
    


```python
#Aşağıda verilen iki boyutlu ve üç boyutlu arrayi oluşturalım. Bu arraylerin boyut, eleman sayısı, satır, sütun bilgilerine ulaşalım.

#İki boyutlu array: [[1,2,6,7], [4,3,9,5]]

#Üç boyutlu array: [[[7,5,14],[21,8,11]], [[8,6,20],[14,3,9]]]

array = np.array([[1,2,6,7],[4,3,9,5]])
print(array)

```

    [[1 2 6 7]
     [4 3 9 5]]
    


```python
print(array.ndim)
```

    2
    


```python
print(array.size)
```

    8
    


```python
array[0,]
```




    array([1, 2, 6, 7])




```python
array[0,2]
```




    6




```python
np.shape(array)
```




    (2, 4)




```python
array2 = np.array([[[7,5,14],[21,8,11]],[[8,6,20],[14,3,9]]])
print(array2)
```

    [[[ 7  5 14]
      [21  8 11]]
    
     [[ 8  6 20]
      [14  3  9]]]
    


```python
print(array2.ndim)
```

    3
    


```python
print(array2.size)
```

    12
    


```python
array2[0,1]
```




    array([21,  8, 11])




```python
array2[0,1,2]
```




    11




```python
np.shape(array2)
```




    (2, 2, 3)




```python

```
