
# Data types that represent **ordered sequneces of values**

## List   
Mutable data type     
**something about ???assign argument??? here**    
When you assign a list to a variable, you are actually assigning a **list reference** to a variable.   
Python uses **references** whenever variables must store values of **mutable** data types.    
Technically, you can only say **variables contain references** to **mutable** data-type values(e.g list, dictionary)  
After the reference to a list is passed to a function, a return value is not used to assign a new value to list.   
Instead, it modifies the list **in place**, directly.   
## List-like types    
### Strings    
Immutable data type    
**A string cannot be mutated. You can only create a new string, making use of the old one.**     

### Tuple   
Immutabe data type  

### Convertion    
```
>>>tuple(['a','b ','c'])
('a','b ','c')      
>>>list (('a','b ','c'))      
['a','b ','c']
>>>list ('abc')         
['a','b ','c']
```    
