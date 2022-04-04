For Loop

    Below is an example of the proper syntax, and the corresponding explanation

    for (statement1; statement2; statement3){
        //your code to be executed
    }

    Explained:
        Statement1: executed once before the execution of the code
        Statement2: defines the condition for executing the code block
        Statement3: executed every time after the code block has been created

For In Loop

        for (property key in object) {
        // code block to be executed
        }

    This was hard for me to grasp, so here is the example from

        const person = {fname:"John", lname:"Doe", age:25};

            let text = "";
            for (let x in person) {
            text += person[x];
            }

    Explanation:
        -The for in loop iterates over a person object
        -Each iteration returns a key (x)
        -The key is used to access the value of the key
        -The value of the key is person[x]

While Loop

    while(condition){
        //code block to be executed
    }

    Explanation:
        as long as (condition) is true, the code will be executed

Do While Loop

    do{
        //code block to be executed
    }
    while (condition)

    Explanation:
        do{} executes the code block AT LEASE ONCE, whether the (condition) is TRUE OR FALSE.

Break

    Explanation:
        jumps out of the loop

```

```

Object Literal

    let user = { //objects & their properties are mutable, even w/ (const) function

        color: 'whatever' , //the comma is a NECESSITY to seperate key-value pairs
    }

    Explanation

        color = is the KEY, it can be any data type
        'whatever' = is the VALUE

Dot Notation

        user.color

    Explanation:
        user = object
        . = dot operator
        color = property name

Method

    let user = {
        color:'whatever',
        read () {
            console.log('I must read a book today!')
        }
    }

    Explanation:

        Method = a function as a property. A property is, method DOES ().

Value types (Primitives) vs Reference Types (Objects)

    Value(Primitives):
        Number
        String
        Boolean
        Symbol
        undefined
        null
                Primitives are copied by their VALUE

    Reference(Objects):
        Object
        Function
        Array
                Objects are copied by their REFERENCE
