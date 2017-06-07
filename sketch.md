## Concepts and Data Learned
1. Float - 23.5
2. Integer - 5
3. String - "Hello"
4. Boolean - True/False
5. Array - ["Lena", "House", 4]
6. Object Hash - {key : "Value"}
7. Data - Facts
8. Information - Knowledge
9. Database relationships:
    * Belongs-to - Related to
    * Has-many - 
    * One-to-one - For each X there is only one Y, and for each Y there is only one X
    * Many-to-many - For each X there are many corresponding Ys, for each Y there are many corresponding Xs

## Q&A 
How do we store the data? 
Objects vs. Variables:
- Objects have things that the thing is and things that 
- Can name anything that exists within code, 
- When you create a variable, you can have a name that is pointing to a function, as opposed to pointing to various 
- Variable can be created for any of the numbered things abvoe, it can also be used to point to a function 
    - name = "Lena"
        - in the example above, 'name' is the variable 
- declaration: setting the sage, this is how things behave, "making the pie"
    name = "Lena"
    sayMyName(arg) {
    alert('hello #{arg}') ; 
    }
    Note: {} means you are doing something in a block
    Note: () function to say name
     
person = {
name: "Lena",
age: 23,
location: "Chicago"
jump: function (){
    do something; 
}
talkTo(person, mood){
    console.log('Hi #{person}, I'm #{mood},
    lets talk about #{subject}')
}
}

Note: if you wanted to create a different person, youd have to reenter everythin again. so instead, you can create a prototype function so that each time a similar object is created, the function will be applied to each one. 
Note: Can set functions within the object if its a one time object, 

GOOGLE: Object literal vs. Object ...
     
- invocation: innitializing the function, "eating the pie"
    name // "Lena"
    sayMyName(name) // "Hello Lena" Alert!
    
    
    