## list
* x = list or x = list()
* list('xyz')
    * change "xyz" into ['x','y','z']
* list(tuple)
    * change a tuple into a list
* x.extend(y) or x +=y
    * using to intergate x with y 
* x.insert(key, value)
*del x[i]
    * using to delete x[i]
* x.remove(value)
    * for example x[3]="test" if we use x.remove('test") x[3]'s orginal value will be removed
* ', '.join(x)
    * x = ['mark', 'tung', '123456']
    * ', '.join(x) will be mark, tung, 123456
* if wnat to copy x to y do not using y = x
    *       using y = x.copy()
    *       y = list(x)
    *       y = x[:]
## dictionary

 dictionary = { 
    'key1':'value1',
    'key2':'value2',
    'keyn':'valuen'
    }
   
* x.update(y)
    * if x and y have same key then we will get y's value
* del x[key]
* x.clear() or x = {}
    * remove all 
* x.get('key')
* x.keys()
    * get all keys of x
* x.values()
    *get all values of x
* x.items()
    *get all keys and values of x 
## set
* empty_set = set()
    * establish a empty set(only have key)
    * do not use empty_ser = {} or it will be a dictionary
* a & b or a.intersection(b)
* a | b or a.union(b)
* a - b or a.difference(b)
* a ^ b or a.symmetric_difference(b)  (xor)
* a <= b or a.issubset(b)
* a < b (proper subset)
* a >= b or a.issuperset(b)
* a > b (proper superset)

