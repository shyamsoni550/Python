#immutable : memory ke andar ka refrence kabhi change naho hota
//immutable means the object can't be changed after it is created. 
    
example : username= 'hitesh'
          username= 'chai'
          print(username)  --> output: chai
                           --> but we want output : hitesh

solution : use tuple instead of variable for immutable data type

>>> x=10
>>> y=x
>>> x
10
>>> y
10
>>> x=15
>>> x
15
>>> y
10

refrence of x is changed but not same for y 