 ***I.Javascript***:

***1. Object:***

- object can be created using ```one of two syntaxes```: 

  + *let user = new object ()*;
  
  + *let user = {}*;
  
- examples:

***a)  Key and value: *** 

```
  let user= {       // an object
     name:"jone" ,  //by key "name" store value "John"
     age: 25      // by key " age" store value "25"
     }
```

  ![Atom](http://javascript.info/article/object/object-user@2x.png)
    
==> you can add or remove and read file from it any time

***b)  Accessible using the dot notation: ***

```
  alert( user.name ); //accessible **name** ==> jone.
  alert( user.age);   //accessible **age** ==> 25.
```

***c) The value can be of any type.***

 Let’s add a boolean one:
 
 ``` 
  user.isadmin= true;
```

  ![Atom](http://javascript.info/article/object/object-user-isadmin@2x.png)
  
***d) you can remove with `Delete` : ***

    ``` Delete user.age;   ```
    
   ![Atom](http://javascript.info/article/object/object-user-delete@2x.png)
   
***e) you can also use multiword property names, but then they must be quoted:***

  ```
    let user ={
        name= " join",
        age = 25,
        'mickey': true
        }
   ```

![Atom](http://javascript.info/article/object/object-user-props@2x.png)

***Note**
              
- We can use square brackets( dấu ngoặc vuông)  in an object literal. That’s called computed properties.

    ```
      let fruit = prompt("Which fruit to buy?", "apple");
      let bag = {
          [fruit]: 5, // the name of the property is taken from the variable fruit
                };
      alert( bag.apple ); // 5 if fruit="apple"
    ```
    
 or 
 
    ``` 
      let fruit =prompt("which fruit to buy?", "apple");
      let bag ={};
      bag[fruit]=5;
    ```
    
or 

    ``` 
      let fruit = 'apple';
      let bag= {
          ['apple' + ' orange' ] : 5;   // bag.appleorange=5;
          };
    ```
    
- Properties:

    ```
        let obj={
          a=1, 
          b=2,
          return=3
          }
        alert(obj.a + obj.b + obj.return); //6
     ```
     
     
*** prompt and print ***


      ```
          function dieuthuy()
            {
                let name= prompt ("name? ");
                let age = prompt ("age?" );
                return = {
                name : name,
                age : age;
                };
            let user= dieuthuy();
            alert(user.name + user.age);
        ```
      
   `name: name` ==> `name,`
      
   `age:age` ==> `age,`
      
again:

 ```
          function dieuthuy()
            {
                let name= prompt ("name? ");
                let age = prompt ("age?" );
                return = {
                name,
                age,
                };
            let user= dieuthuy();
            alert(user.name + user.age);
```
                
- Existance check:

  + using ` "key " in  object `
  
  ex:
  
    ```
        let user={
            name="jonh",
            age= 15
            }
        alert("name" in user);    // true       ;     user.name  is exist
        alert("last" in user);    //false       ;     user.age   is not exist
    ```
    








